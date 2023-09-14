# neuropixels_2.0_implant_assembly
CAD files for a chronic implant assembly for test-phase Neuropixels 2.0 probes in rodents. The design is closely based on the design for the 1.0 implant assembly described and validated in [Luo*, Bondy* et al](https://elifesciences.org/articles/59716) 
with print files available at [this repo](https://github.com/Brody-Lab/chronic_neuropixels).

The assembly consists of four discrete parts: (1) a [dovetail adapter](https://www.janelia.org/open-science/neuropixels-probe-mounts-10-prototype-10-production-and-20-production-versions) permanently glued to the probe base (designed by Wade Sun and the Harris lab at Janelia); (2) an internal holder that mated with the dovetail adapter and allowed stereotaxic manipulation of the probe; (3-4) an external chassis, printed in two separated parts, that encased and protected the entire assembly. The external chassis and internal holder were attached using screws that could be removed at the end of the experiment to allow explantation and reuse. The dimensions of the 2.0 assembly were significantly smaller, primarily because of the smaller size of the probe and headstage. The maximum dimensions were 24.7 mm (height), 12.2 mm (width), and 11.2 mm (depth), with a weight of 1.5g (not including the headstage). This size and weight made the assembly suitable for chronic implantation in both mice and rats. 

The links above are to .stl or .step files for the individual parts. The parts are assembled in the Inventor file linked here. Additionally, we provide a .form file that can be directly printed on Formlabs 3D printers.

Note: Dimensions have been tested exclusively using a Form 3 printer, with Black V4 resin and the finest resolution (25um). 
Dimensions will likely need to be adjusted if printed using another method. 
In particular, the parameter "dovetail_gap" in the Inventor file (.ipt) is highly sensitive, and determines how well the probe dovetail mates with the holder. 
This has been highly optimized not just for the print settings listed above, but also the angle of the part in the print file. 
For best results, use the .form file instead of laying the parts out yourself using the CAD files.
The .form file included in the repo prints 5x each part, using the 65um gap version of the internal holder.
The .stl files are exports of the individual parts in the .ipt file.


