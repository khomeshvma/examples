# Example Templates

This repository contains example Templates for common images on the Digital Garage. For more information about Templates 
how to use them, see the official Digital Garage documentation on [Image Streams](http://docs-test-digitalgarage-docs.apps.thedigitalgarage.io/architecture/core_concepts/templates.html)

To deploy an Image Stream to your project on Digital Garage use the following command from the Digital Garage CLI in your project:

```
oc create -f https://raw.githubusercontent.com/thedigitalgarage/examples/master/image-streams/<<your-image-stream>>.<<json/yaml>>
```

Once loaded, select the ``your-image-stream`` Image Stream from the web console when wanting to add a new image to the project.
