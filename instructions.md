# INSTRUCTIONS FOR PROJECT FROM INSTRUCTOR


You have a choice of several options for the final project.

## Option 1: WebGL Animated Game
If you choose this option, the goal is to synthesize everything you've learned in WebGL so far and construct an interesting and elaborate animated game. It does not have to be a game in the traditional sense - it could be anything that is interactive and has some overall goal that the user is trying to achieve (solve a maze, find certain types of objects, etc). The high-level idea is that the user will control some aspect of the game (usually the movements of a character through a world) using the keyboard/mouse.

Note: I expect that most people will choose this option or the second one, unless you really want to go into depth with Blender. Instructions for the Blender-only option are below.

**Requirements:**   
*Blender Character:* First, create a 3D "character" model in Blender, and export it into a suitable format format (see Homework 9) for use in WebGL. It does not necessarily need to be human or animal like, but it should be reasonably sophisticated (i.e. not just a square or sphere). For the hierarchical modeling part below, it might be helpful to create some of the character's body parts as separate 3D objects, so that their movements can be isolated and controlled.    
*Hierarchical Modeling:* There should be some hierarchical modeling aspect to your project (i.e. using the idea of "container" objects to create a movement hierarchy). This could be moving your character's body parts with different keyboard keys (like the robotic arm). Or it could be that some aspects of the world are moving on their own using a hierarchical model (like the solar system we did for homework).    
*Game Play:* The user can either control the animated character with keyboard input, or interact with the character in some way. One example would be to have two characters; one moves randomly, and the user controls the other through keyboard movements. The goal would be for the user's character to either chase or run from the other character. Or there could be tokens to collect for a score. It doesn't have to be a win/lose game, just some way for the user to interact with the world in a goal-oriented way.    
*World and Camera:* The character should be moving around in a 3D "world". I want this to be open-ended, but there should be some context (i.e. floor, walls, a room, an outdoor scene, objects, other characters). It doesn't have to be realistic, but the camera viewpoint should give the sense that the user can move in the space. In Homework 6 the camera was meant to be in the same place as the viewer's eye. In this assignment, if you have a character, the camera should be a bit away from the scene so that it captures the character's movements (3rd person viewpoint). It could track the character, or be fixed so that the entire scene is always visible.    
*Lighting:* Use at least one light source, and additional ones if desired -- enough to clearly illuminate the world.    
*Texture Mapping:* At least part of the character or part of the world should be texture mapped, including either a normal map or a bump map.    
*Readme:* To explain the game play, create a readme.txt file with instructions for me. Clearly explain the goal of the game and how I should use the keyboard/mouse to play it. If you used a particular web browser to run your program, let me know that too. I will not debug your code - make sure everything is included so that it will work out of the box. If I have to guess, you may not get the credit you deserve.    
*Submit:* Submit all the following files:    
* final_project.html (main WebGL file)
* Any .blend and .glb files, if you created objects in Blender for importing.
* any texture image files, normals, and/or bump maps
* any libraries necessary to run your code, other than three.min.js.
* readme.txt

*Optional:* Hosting your Project: If you would like me to host your project (so that you can send a link to friends/family) please let me know - I would be happy to! This means that your project will be publicly visible to anyone with the link. Email me after you submit your project and I will put it up (note that this will be a lower priority than grading, so it might not happen very quickly). Alternately, you can get your own hosting space through ITS and put it there.

**Resources:**
To help get you started, I have created some demo projects showing examples of specific techniques that may be useful to you as a starting point. I wouldn't expect your game to look just like any of these; rather, you should adapt the technique shown in a way that is appropriate for your own project.

*Side Scroller:* This is an example of one way to get an infinitely unrolling landscape. The scene is actually a giant platter rotating relative to the camera. What seems like an endless landscape is really a large circle.    
*Planar Motion:* This shows a method of moving an object in any direction over a plane, with third-person following camera.    
*Collision Detection:* This shows an object moving in 3D, detecting collisions with a 3D environment imported from a GLTF file.    
*Grid Move & Jump:* This two techniques: an object moving in discrete steps on a grid (arrow keys), and a jump (space bar).    
*Planar Grid with Zones:* This shows a character moving across a planar board, with detection as it crosses color boundaries. In addition, the player is prevented from moving into the red zone.    
*3D Terrain Intersection:* This shows a pointer moving across a 3D terrain. Collision detection determines the height of the terrain at the current XY location.    
*AABB Collisions:* This shows how to do rough collision detection using axis-aligned bounding boxes and an object loaded from a GLTF file.    


## Option 2: Animated Short Movie
This option is a variant on the game design described above. The idea is to create an original short animated movie using the programming tools we have learned. It is expected that your movie will be similar in complexity to the game option described above, except that instead of being under player control, the animation will be scripted in advance and follow a predetermined plot. It should last long enough to show off what you have learned, and provide a satisfying experience for the viewer.

You will follow most of the requirements listed above for the game. Your movie should feature at least one character sculpted by you in Blender, use hierarchical modeling, and feature a 3D world with lighting, texture, and well-chosen camera angles.

In place of gameplay, your movie should have a plot that tells an interesting story. The movie may feature more than one scene, or it might happen all in one place. Pay some attention to the "set" of your movie -- the background and environment. It is ok to bring in 3D models created by others, so long as you credit them and they fit in with everything else you are creating. You should include a readme.txt file that summarizes the plot, and credits any resources used.

*Demo:* This short clip shows use of a GLTF character with a palette of animations, simple plot, and changing camera angles.


## Option 3: Photo-realistic Image in Blender
This option is only for those who really want to become experts in Blender. If you choose this path, I expect that you will undertake self-directed learning of Blender techniques that go beyond what we covered in class. There are lots of online tutorial videos that will teach you various aspects of the program. Although I encourage you to use these tutorials for learning, the image you submit to me must be your own creation and not from following a tutorial.

To take this option, you must find a suitable image and email it to me for approval and your reasons for wanting to learn more about Blender. Email me by Tuesday, May 4. To ensure that you are extending yourself, your image should fulfill certain guidelines:

It must be an actual photograph. The real world has a richness and depth that cannot easily be duplicated. Recreating someone else's rendering does not measure up.   
It should include a sufficient amount of detail to make for an interesting render. Landscapes and distant buildings typically fall short in this regard. If you wish to render a scene with mostly distant objects, you may do so as long as you either include objects in the foreground, or include a second viewpoint showing close-up detail.    
It should include a variety of different materials and other types of features. For example, consider fabrics, liquids, plants and other natural materials, transparency, lights, and so on.    
The idea is that your rendered image will look as much like a photograph as possible. In some cases, if you cannot find a reference image that looks exactly the way you want, you can combine features from more than one image (e.g., object from one image in a setting from another). You may also plan to leave out one or more unwanted features from the reference image, so long as what remains satisfies the criteria above (e.g., leave out a car that is in front of the building you want). If you plan to modify the reference in this way, please let me know when you submit the image for approval.

**Requirements:**   
*Find a photo:* Start with an existing photo you want to reconstruct in Blender. It could be a photo you've taken or a photo you find. Submit this photo along with your work. If you start with an easier photo, the standard for a realistic version will be higher, and visa-versa. Still life style photos are often a good choice. In any case, the photo should include sufficient detail to provide some challenge, as described above.   
*World and Camera:* The camera should be placed in a similar position to where the real camera was. The scene should be created in a 3D fashion (as opposed to trying to construct the image using 2D shapes).    
*Lighting:* Use as many light sources as necessary to create the lighting effects of your photo (there should be at least one).    
*Texture Mapping:* Use at least two textures in your image, at least one with with a normal map or bump map.    
*Journal & Reflection:* Keep a journal of your modeling process, documenting time spent on each part of the image as you added it, plus any roadblocks or challenges you had to solve along the way and how you managed them. Include periodic screenshots of your progress. At the end, write a short reflection about your image and what you learned from creating it.    
*Submit:* Save both a .blend file and a .jpg or .png file of the final rendered image. Zip all your files (including the journal and reflection) and submit the zip folder on Moodle. If you wish, you may submit additional images of your scene, but the first should match the photo that served as inspiration.    


## Option 4: Write Your Own Ray-Tracer
This is by far the most difficult option, and the most open-ended. Write a ray tracer that can render, at minimum, spheres with reflections and shadows, in a language of your choosing. A ground plane would be nice also. It should take as input a text file describing the scene geometry (objects and lights) in some simple format of your devising. For example, you can list the type of object and the parameters necessary to construct it:

Sphere 2 4 1 3   
Sphere 12 -3 5 7    
Plane 0 0 -6    
You can find code for ray tracers on the Web. Resist the temptation to look at them. You may, however, make use of resources describing their construction, including assignments similar to this one (e.g., here).

*Journal & Reflection:* Keep a journal of your development process, documenting the order in which you developed and tested your code, including the amount of time spent on each section. Mention any significant roadblocks or challenges you had to solve along the way and how you managed them. At the end, include a short reflection about your program, what you learned from creating it, and how you might develop it further.

*Submit:* I will need your code along with the development journal. When you have finished the project, use your ray tracer to render two different scenes with at least two light sources and three objects each. Include the input files used, and the images they produced. Also write short readme.txt describing the input format, instructions for compiling and running the program, and details on how I can use your program to create a new image of my own design.


## Submit your Work
Whichever option you choose, submit on Moodle all the files needed to view and evaluate your work. Be as complete as possible. Final projects should be individual (no pair programming on the final project).