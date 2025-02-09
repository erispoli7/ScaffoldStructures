This is a fork of the code described in "Open Source Software for the Automatic Design of Scaffold Structures for Tissue Engineering Applications" for use in PJAS/PRSEF 19-20


## What it does:
You can generate minimal surface structures in any desired dimension and save them as .stl-file. An overview of the possible scaffolds/structures follows below.

## How to run?

You can find **an executable** in the release page here: https://github.com/Spanholz/ScaffoldStructures/releases/tag/v0.2-alpha

The software was tested with Python 3.7 under Ubuntu 19.04. 

Or open the folder in Terminal and run it with: `python app.py`
Needed packages are:
- numpy
- vtk
- pypubsub
- wx

## Explanation of the sliders:
- **Number of primitive cells in X,Y,Z direction** - changes the number of unit cells in each direction

- **Quality factor** - changes the surface quality of the structure, lower values took longer to render

- **Wall thickness** - changes the thickness of the wall seen from the surface of the minimal surface structure




## Overview of the different possible scaffolds

Currently the following triply periodic minimal surfaces are available:

 - Schwarz P ![SchwarzP](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/SchwarzP.PNG)
 - Schwarz D ![SchwarzD](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/SchwarzD.PNG)
 - Gyroid ![F-RD](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Gyroid.PNG)
 - F-RD ![F-RD](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/F-RD.PNG)
 - Neovius ![Neovius](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Neovius.PNG)
 - iWP ![iWP](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/iWP.PNG)
 - L-Type ![L-Type](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/L-Type.PNG)
 - G' ![G'](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/G_prime.PNG)
 - Tubular G ![Tubular G](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Tubular_G.png)
 - Tubular P ![Tubular P](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Tubular_P.png)
 - P_W_Hybride ![P_W_Hybride](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/P_W_Hybrid.PNG)
 - I2-Y ![I2-Y](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/I2-Y.PNG) 
 - Skeletal 1 ![Skeletal 1](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Skeletal_1.png)
 - Skeletal 2 ![Skelatal 2](https://github.com/Spanholz/ScaffoldStructures/blob/master/images/Skeletal_2.png)


## License

This app was originally developed by J.C. Dinis at Centre for Rapid and Sustainable Product Development, Polytechnic Institute of Leiria, Marinha Grande, Portugal.

It is open-source and available under GNU GPLv2.0.

Link to the original paper:
https://doi.org/10.1016/j.protcy.2014.10.176
