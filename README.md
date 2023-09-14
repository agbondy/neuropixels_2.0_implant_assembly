# neuropixels_2.0_implant_assembly
CAD files for a chronic implant assembly for test-phase Neuropixels 2.0 probes in rodents.

Closely based on the design for the 1.0 implant assembly published in [Luo*, Bondy* et al](https://elifesciences.org/articles/59716) 
with print files available at [this repo](https://github.com/Brody-Lab/chronic_neuropixels).

Dovetail adapter/mount for the probe was designed at Janelia and is available [here](https://www.janelia.org/open-science/neuropixels-probe-mounts-10-prototype-10-production-and-20-production-versions)

Note: Dimensions have been tested exclusively using a Form 3 printer, with Black V4 resin and the finest resolution (25um). 
Dimensions will likely need to be adjusted if printed using another method. 
In particular, the parameter "dovetail_gap" in the Inventor file (.ipt) is highly sensitive, and determines how well the probe dovetail mates with the holder. 
This has been highly optimized not just for the print settings listed above, but also the angle of the part in the print file. 
For best results, use the .form file instead of laying the parts out yourself using the CAD files.
The .form file included in the repo prints 5x each part, using the 65um gap version of the internal holder.
The .stl files are exports of the individual parts in the .ipt file.


