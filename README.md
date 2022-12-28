# SlopeWAuto
Automate SlopeW

Model

1. Slope/W file is prepared
2. Extract XML file from .GSZ
3. Modify XML file
4. put XML file back inside .GSZ archive
5. Run analysis with GeoCmd.exe
6. Extract results

Note -SlopeW format .GSZ is a compressed folder with XML(data) and PLY(Mesh) file -GeoCmd.exe can only run analysis, it cannot modify models

Input

-For: Slope/w files #1-n -For: Excel with parameters to swap

Output

-Amended Slope/w files (optional) -Excel results (for comparison, not presentation)

Additional -Modify geometry?

Libraries needed

pip install pyunpack pip install patool
