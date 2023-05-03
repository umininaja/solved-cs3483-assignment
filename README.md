Download Link: https://assignmentchef.com/product/solved-cs3483-assignment
<br>
<strong>In the assignment, you are required to use p5.js and ml5.js to develop an interface for viewing and interacting with an image.  These actions are performed by using face detection and keyboard operations. </strong>

<h1>Detailed Requirement</h1>

<h2>1. Initial Setup</h2>

Create a display window.

Load and display an image in the window.

The instant view of the camera should be displayed next to the image and has the same size as the image.

2. Face detection

A rectangle should be drawn on the camera view to indicate the position and size of the detected face.  When you move your face in front of the camera, the rectangle should keep following your face.  A corresponding position indicator should also be drawn on the image to follow the movement of your face.

3. Viewing the image

When the ‘<strong>v</strong>’ key is pressed and released, the interface should enter the <strong>view image</strong> mode. In this mode, a blurred version of the image should be displayed. When your face is moving in the camera view, a rectangular area around the position indicator in the blurred image should display the corresponding region from the original image without blurring.  When the position indicator moves away, the blurred appearance of the image region should be restored.

4. Replacing the faces

When the ‘<strong>f</strong>’ key is pressed and released, the interface should enter the <strong>replace face</strong> mode.

In this mode, the original image should be displayed. When your face is moving across the camera view and the corresponding position indicator is close to a face in the image, the face should be replaced by the camera view of your own face at a compatible size. When the position indicator moves away, the original face in the image should be re-displayed.




<h2>5. Exiting the view image/replace face mode</h2>

When the ‘<strong>e</strong>’ key is pressed and released, the interface should exit from the <strong>view image/replace face</strong> mode, and the original image should be re-displayed.


