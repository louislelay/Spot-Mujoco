### Spot-Mujoco

This repository contains a Mujoco model of Spot, created with MJCF modeling language. 

I found .stl and .dae files, along with a spot.urdf.xacro file in this repository :

https://github.com/SoftServeSAG/spot_simulation/tree/spot_robomaker

I converted the .dae files to .obj format via Blender, I used obj2mjcf command like recommended in the Anymal C documentation of the Mujoco Menagerie. 

I've coded the spot.xml file, structured based on the Anymal C XML, while using parameters from the spot.urdf.xacro file.

https://github.com/louislelay/Spot-Mujoco/blob/main/spot.png