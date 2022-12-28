# SlopeWAuto
Automate SlopeW

Note -SlopeW format .GSZ is a compressed folder with XML(data) and PLY(Mesh) file -GeoCmd.exe can only run analysis, it cannot modify models

Model

Slope/W file is prepared
Extract XML file from .GSZ
Modify XML file
put XML file back inside .GSZ archive
Run analysis with GeoCmd.exe
Extract results
Input

-For: Slope/w files #1-n -For: Excel with parameters to swap

Output

-Amended Slope/w files (optional) -Excel results (for comparison, not presentation)

Additional -Modify geometry?

Libraries needed

pip install pyunpack pip install patool
