
CAD files for a chronic implant assembly for test-phase Neuropixels 2.0 probes in rodents. The design is closely based on the design for the 1.0 implant assembly described and validated in [Luo*, Bondy* et al](https://elifesciences.org/articles/59716) 
with print files available at [this repo](https://github.com/Brody-Lab/chronic_neuropixels).

The assembly consists of four discrete parts: (1) a [dovetail adapter](https://www.janelia.org/open-science/neuropixels-probe-mounts-10-prototype-10-production-and-20-production-versions) permanently glued to the probe base (designed by Wade Sun and the Harris lab at Janelia); (2) an [internal holder](internal%20holder%2065um.stl) that mates with the dovetail adapter and allowed stereotaxic manipulation of the probe; (3-4) an external chassis, printed in two separated parts [here](external%20chassis.stl) and [here](external%20top.stl), that encases and protects the entire assembly. The external chassis and internal holder are attached using screws that can be removed at the end of the experiment to allow explantation and reuse. The dimensions of the 2.0 assembly are significantly smaller than the 1.0 assembly on which it is based, primarily because of the smaller size of the probe and headstage. The maximum dimensions are 24.7 mm (height), 12.2 mm (width), and 11.2 mm (depth), with a weight of 1.5g (not including the headstage). This size and weight make the assembly suitable for chronic implantation in both mice and rats. 

The part files linked above (with the exception of the dovetail adapter) were exported from the parent [.ipt (Inventor) file](neuropixels%202.0%20implant%20assembly.ipt). We also provide a [.form file](all_parts.form) that can be directly printed on Formlabs 3D printers.

The link above associated with the dovetail adapter also contains video instructions for mounting it to a probe.

Note: Dimensions have been tested exclusively using a Form 3 printer, with Black V4 resin and the finest resolution (25um). 
Dimensions will likely need to be adjusted if printed using another method. 
In particular, the parameter "dovetail_gap" in the Inventor file (.ipt) is highly sensitive, and determines how well the probe dovetail mates with the holder. 
This has been highly optimized not just for the print settings listed above, but also the angle of the part in the print file. 
For best results, use the .form file instead of laying the parts out yourself using the CAD files.
The .form file included in the repo prints 5x each part, using the 65um gap version of the internal holder.
The .stl files are exports of the individual parts in the .ipt file.

### Assembling the implant once the parts are printed
See this excellent [assembly instruction manual](https://docs.google.com/document/d/1IJHo09xTRHtCSInflJ-By5AF2hARtQX3Hh1mwAKbEYk/edit?usp=sharing) written by Sarah Jo Venditto.
