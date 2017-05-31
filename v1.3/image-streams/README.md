# Example Image Streams

This repository contains example Image Streams for common images on the Digital Garage. For more information about Image Streams 
how to use them, see the official Digital Garage documentation on [Image Streams](http://docs.thedigitalgarage.io/architecture/core_concepts/builds_and_image_streams.html#image-streams)

To deploy an Image Stream to your project on Digital Garage use the following command from the Digital Garage CLI in your project:

```
oc create -f https://raw.githubusercontent.com/thedigitalgarage/examples/master/image-streams/<<your-image-stream>>.<<json/yaml>>
```

Once loaded, select the ``your-image-stream`` Image Stream from the web console when wanting to add a new image to the project.
