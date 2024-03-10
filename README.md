# RhinoPTE

A tool to generate Pen Text Engines for Scratch.

To use, you must have [Rhino 7](https://www.rhino3d.com/) installed. You will also be using [Grasshopper](https://www.grasshopper3d.com/) which is included in the software.

Grasshopper requires the plugin EleFront which can be downloaded here:
https://www.food4rhino.com/en/app/elefront

ChopChop is also used but can be ignored as it has no functional purpose for the end user (it's used for editing the script):
https://www.food4rhino.com/en/app/chopchop

## Usage
Download this repository. 

Open `chars.3dm` in Rhino and then `chars.gh` in Grasshopper. The Rhino file is where you draw characters. The Grasshopper file holds all the code and settings. 

To design a full set of characters, set up the specifications in Grasshopper along the left edge of the script. This includes maximum size of a character and where the origin should be (bottom-left of every character bounding rectangle should touch it). 

Now you can start adding polylines and points in Rhino. Grasshopper generates reference lines for alignment. 1 Rhino grid unit = 1 pixel in Scratch.

Finally, click the generate button in Grasshopper to generate and save the sb3 file with the PTE already set up in the output folder.

An example project generated with this tool can be seen here: https://scratch.mit.edu/projects/934459716
