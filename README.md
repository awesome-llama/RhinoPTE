# RhinoPTE

A tool to generate Pen Text Engines for Scratch.

To use, you must have Rhino 7 installed as well as being able to use Grasshopper (which is included in the software).

https://www.rhino3d.com/
https://www.grasshopper3d.com/


Grasshopper requires the plugin LunchBox which can be downloaded here:
https://www.food4rhino.com/en/app/lunchbox
ChopChop is also used but can be ignored as it has no functional purpose for the end user (it's used for editing the script).

## Usage
Open both `chars.3dm` and `chars.gh`.
The Rhino file is where you draw characters. The Grasshopper file holds all the code and settings. 

It is very easy to design a full set of characters. Firstly in Grasshopper set up the specifications like maximum size of a character and where the origin should be (bottom-left of every char bounding rectangle should touch it). Then start adding polylines and vertices to Rhino's viewport. Once done, click the generate button on Grasshopper to generate and save the sb3 file with the PTE already set up.

An example project generated with this tool can be seen here: https://scratch.mit.edu/projects/934459716