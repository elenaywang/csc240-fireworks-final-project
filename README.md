# csc240-fireworks-final-project

*Title of project:* Fireworks      
*Contributor(s):* Elena Wang      
*Course:* CSC 240 Computer Graphics, Fall 2021      
*Instructor:* Nick Howe      
*Timeline:* December 2021      

*Link to demo on Replit:* https://6d72454c-c454-4c0d-8180-9861bc7ae124-00-38z49jteozqjg.global.replit.dev/

### *How to run this project:*       
To run a demo of this project, simply click the link above. The project will immediately begin running as soon as the window is opened.

### *Overview:*      
This is my final project for the CSC 240 Computer Graphics class at Smith College. Out of the four project options, I chose the "Animated Short Movie" option. My main goal for this project was to learn how to use particle systems in three.js to simulate fireworks. I also incorporated multiple computer graphics concepts that we learned over the Fall 2021 semester, including texture mapping, hierarchical modeling, and camera movement.

### *What this project does:*     
The camera circles around a panda who is watching fireworks in a grass field while jumping up and down in excitement. The fireworks consist of particle systems that have randomly generated colors, locations, and sizes. The panda consists of a Blender model and three.js meshes organized in a hierarchical model. The ground and sky consist of texture mapped-three.js meshes.    
(Side note: I tried adding point lights in the center of the fireworks, but doing so causes the animation to lag. I've commented out the corresponding lines of code so that the animation can run properly.)

### *What I used:*      
The 3D panda model was created in Blender. The code was written in JavaScript. I used the [three.js library](https://threejs.org/) to create and display 3D graphics and used [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader) to import GLB files into three.js. The sources for the texture maps and coding help are listed below.

*Resources:*    
1. Particle system code: CSC 240 Lab 15   
2. Using particles in three.js: https://aerotwist.com/tutorials/creating-particles-with-three-js/   
3. Creating a skybox: https://threejs.org/manual/#en/backgrounds   
4. Creating a skybox: https://codinhood.com/post/create-skybox-with-threejs    
5. Importing a Blender model into three.js: https://youtu.be/ZUviQP1L9uw     
6. Changing colors/material of faces in Blender: https://youtu.be/grwK8QB2DkU    
7. Keeping track of multiple fireworks: https://youtu.be/CKeyIbT3vXI    

*Texture map sources:*    
1. particle.png: CSC 240 Lab 15    
2. grass-texturemap.png & grass-bumpmap.png: https://renderman.pixar.com/pixar-one-twenty-eight    
3. nightskycolor.png: https://opengameart.org/content/night-sky-stars-and-galaxies    
4. white-fur-texture.jpeg (for panda Blender model): https://www.myfreetextures.com/a-seamless-soft-white-fur-texture/

### *Files:*   
* index.html: contains the HTML and JavaScript code for the entire project
* GLTFLoader.js: loads glTF files into three.js
* grass-bumpmap.png: bump texture map to create the appearance of 3D grass texture
* grass-texturemap.png: color texture map to create the appearance of grass on the ground
* instructions.md: contains the instructions for this project as provided by the course instructor, Nick Howe
* nightskycolor.png: color texture map to create the appearance of a night sky
* panda.glb: GLB file for 3D Blender model of panda character
* particle.png: color texture map for the individual firework particles
* README.md: contains information about the project
* three.min.js: contains the three.js library
