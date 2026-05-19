<head>
	<title>Rise And Fall</title>
	<style>
	  body {
	    background-color: #131313;
	    color: #d0d0d0;
	  }
	</style>
</head>
# Boids Engine
<img src="../Assets/BE/BEBoidSwarm.png" width="750" />\
This project is an engine made using C++ and OpenGL, using a primitive engine as starting point. I implemented many basic features into the engine. I implemented a Transform class used for the positions of the camera and objects placed in the scene. This Transform makes use of a matrix to store its data. From this I learned a lot about working with matrices and the values inside them, in addition to learning more about other 3D math concepts as well. 

Post-processing has been implemented using framebuffers, and has different effects. The color filter uses a small texture of known color and compares it with fragments onscreen to be set to the closest matching color. The outline filter uses Laplacian edge detection to find large differences in color to detect edges.\
<img src="../Assets/BE/BEColorFilter.png" width="325" /> <img src="../Assets/BE/BEOutlineFilter.png" width="325" />


[GitHub wiki ->](https://github.com/DeGekkeLamas/AdvRendering/wiki) 
[GitHub repository engine ->](https://github.com/DeGekkeLamas/RenderingEngines) 
[GitHub repository documentation ->](https://github.com/DeGekkeLamas/AdvRendering) 