# 3D-Rotating-Cube-HCI-Graphics-Project-
A 3D rotating cube with input key_controls for the cube.
Downlaod Freeglut for MSV file from this : https://www.transmissionzero.co.uk/software/freeglut-devel/
extract the .rar file 
put the include folder into (C/C++->General->IncludeLibraries) in your project properties.
put the lib folder into (Linker->General->AdditionalLibrariesDependencies).
put these into ["freeglut.lib,opengl32.lib,glu32.lib"] into (Linker->input).
must include the (Bin/x64/freeglut.dll) into your (C:windows/system32) folder.
