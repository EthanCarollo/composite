# How to Test

To test or develop individual visual components (`.tox` files) independently, follow this process:

1. **Create a new TouchDesigner project**  
   Start with a clean `.toe` file to isolate the component.

2. **Import the `.tox` file**  
   Drag and drop the desired `.tox` from the `Filters/` folder into your new project.

3. **If you don't have a Kinect (v1 or v2):**  
   You can still simulate the input by using one of the **test silhouette images** located in the `test-samples/` folder. These images are designed to mimic the kind of data a Kinect would provide, allowing you to preview and adjust the visual output.

This method allows for fast iteration and debugging without the full installation setup.
