# PAT64V3_W8

This software partially analyses images taken by the 
[Medium to Large dynamic phenotyping platform](https://www.plant-phenomics.ac.uk/index.php/resources/index.php/resources/lemnatec-system/) 
at the [NPPC](https://www.plant-phenomics.ac.uk). 

In particular, this is the version of the software that was used to analyse the 'W8' wheat experiment.

## Outputs

PAT64V3 will calculate things like the height of the plant, as well as the area presented to the camera.

## Dependencies/Installing/Running

This software depends on [OpenCV](https://opencv.org/), and will probably only compile
with [Visual Studio](https://www.visualstudio.com/).

In this form, this software will only run on Microsoft Windows, as the backslash ('\\') has 
been hard coded as the file separator.

I recommend that this project only be used as a reference, ie. to inspect the algorithm's
and OpenCV functions used to analyse the images.  

## Author

This software was written by [Dr. Jiwan Han](https://www.plant-phenomics.ac.uk/index.php/about/meet-the-team/)

## PAT64V3_cp

PAT64V3 has been [ported](https://TODO:link_to_PAT64V3_cp) to run on Linux 
and compile with GCC. It is likely that it will also run and compile on most other platforms
including Unix and MS Windows, but this has not been tested.  You should use that version
instead.
