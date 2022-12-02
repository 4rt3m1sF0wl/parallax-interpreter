# parallax-interpreter
A CV identifier for positional object tracking using parallax


This project is not designed to interface with a specific drone or piece of equipment. It takes two feeds of images with defined positions, FOVs, and relative angles of the cameras.

Eventually it should be able to translate from one point to another in an internal map, or head in a direction. It identifies objects in 3 dimensions using parallax to define the distance and size of objects.
I'm not sure if that will work, and I don't think that's parallax. Essentially the system will find objects in its path by comparing two images and finding the differencces. Maybe isolaate objects by color and subtract the difference between them, then calculate the size and distrance by the size of the outline and the relative size and position/image origin of the outlines

This is not being actively worked on so don't expect anything unless you add it. Email me maybe  :D
