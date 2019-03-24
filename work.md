# How Does Digital Fabrication Work?

## 1. Design:

The first step is to create a virtual model of a design using CAD software. To serve as input for the
fabrication tool, the 3D model is exported as a triangulated mesh, which uniformly describes the geometry
in terms of points on the surface or vertices, the faces between those vertices, the edges of those faces,
and in some cases, the normal vectors and color information pertaining to the faces.

## 2. Prepare: 

Print preparation software or slicer software serves as the intermediate between the virtual mesh and the fabricated model for 3D printing. In this step, manufacturing parameters and settings specific to the fabrication tool are added to provide essentially a list of instructions for the machine to follow, resulting in a CAM file that’s sent to the machine. In machining operations, software simulation is combined with user input to generate toolpaths that will guide the cutting tool through the part geometry, taking into account speed of the cutting tool and feed rate of the material.

## 3. Fabricate:

Fabrication tools manufacture parts based on the CAM data, with little or no human assistance or interaction. The fabricated parts might require some form of finishing to achieve their final properties and look before they’re ready to use.