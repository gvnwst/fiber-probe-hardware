# Hardware designs for fiber probing

This is a collection of designs I started creating during my graduate career at MIT. 
I was frustrated by the poor selection of both commercial and custom options for the mounting fiber optics in a manner suitable for probing photonic integrated circuits -- particularly in the case of vertical grating couplers. 
In the history of my lab (at the least, what fraction I am aware of) there were at least four different custom approaches.
The motivations for each varied: simplicity/ease of machining, variability in fiber angle, ability to hold fiber in an intermediate clamp, and so on.

Anyway, these are my version(s). 

## Project structure
In its first iteration, there are just one or two variations of fiber holders, and one type of die mounting chuck. 
Most of my designs are made in solidworks 2018 (as time has gone on, a lot of these are Solidworks 2024), so you'll need to be able to open or convert these files to another format if you want to modify anything. 
Other filetypes (`.stl`, etc) may be made available if there is interest.

Each version of a design should be housed in its own directory and include: 
1. 3D models of all required custom parts, suitable for being sent to rapid prototyping services (`plethora`, `xometry`, and `protolabs` to name three I've used)
    1. If the new design is an update of only _part_ of a previous design, the un-changed 3D models should not be replicated. However, there should exist clear references in...
3. A bill of materials, including non-custom parts (fittings, needles, etc)
4. A document with a brief description of the design and its intended use case. This may be in the same file as the BOM. 
5. A subdirectory, often called `auxiliary files`, that stores *extra* CAD files which may be useful (e.g.  assemblies, `.stl` files for prototyping on a 3D printer). These are not designs that need to be sent out for manufacture.

## A note on license and derivative works
A creative commons license was chosen for this repository, and you the reader are encouraged to use and upgrade these designs! 
I would additionally ask that if you think up a genius improvement, or are inspired to create something better, that you also share those designs publically. 
You can do that here, by making a pull request, or through your own project -- I'm happy to reference other projects in this documentation. 
Anything to avoid some other poor grad student from going through the process, again.


