## Three.js Object Wheel 
To create an image carousel in the form of object wheel using three.js JavaScript library

## Live Site

Scroll up or down and see the carousel move

Demo: https://vermillion-puppy-1ca6b0.netlify.app/


## Screenshot
![image](https://user-images.githubusercontent.com/18692751/228289498-68bc5661-0ef9-4b9a-ad20-2ddf51e796c1.png)


## Overview

- Download three.js library: https://github.com/mrdoob/three.js/archive/master.zip

### Coding Overview

- Step 1: setup a canvas in the html document
- Step 2: create a scene and setup objects
     - load image files using `THREE.TextureLoader`
     - add a filter on the image to sharpen it
     - load an image file into a custom material
     - add image to the group
- Step 3: Add group to the scene      
- Step 4: Setup Camera
- Step 5: Render (add canvas to the DOM and animate)
