[![DOI](https://zenodo.org/badge/632405103.svg)](https://zenodo.org/badge/latestdoi/632405103)

# Surface-tension_Oscillating-droplets
Comsol files for symmetrical and asymmetrical oscillating droplets in 2D and 3D

Author: Kiana Fahimi, University of Bremen Particles & Process Engineering (kfahimi@uni-bremen.de)

-A detailed description of the model equations can be found in: [....]

This repository includes three Comsol Multiphysics 5.6 files. Each file includes a variation of the droplets simulated for the associated paper. There are 2 files with a three-dimensional setup and 1 file with a 2 dimensional set up. The physics principles employed in both 3D and 2D scenarios are identical. Please note that the files do not include the actual solutions (due to increased file size), but they are set up and ready to be run for further analysis.

The defined parameters for the study can be seen under *Parameters*. All parameters can be modified to desired values.

![image](https://user-images.githubusercontent.com/131758702/234258130-0633b9aa-d5f6-459b-9a8b-85050b1f9603.png)

Laminar flow is chosen for this study and the details appear under the node with the same label:
 
![image](https://user-images.githubusercontent.com/131758702/234259858-76b1eafa-550a-45b1-b766-3ffe04a5cf77.png)

Nitrogen and its properties have been added from the comsol material library. Properties of copper (surface tension and dynamic viscosity) are defined under *Fluid Properties - Copper* as follows:

![image](https://user-images.githubusercontent.com/131758702/234260529-0e2fea01-0604-4be3-9c48-8ebd56073f5a.png)

The defined mesh has a higher resolution at the interface. The values can be found under the node with the same name.

![image](https://user-images.githubusercontent.com/131758702/234266153-8cd7e4f7-e580-4ed9-aa87-6066be918502.png)

Initiating the computation can be achieved by selecting *Compute*  located under the *Study* node. In this case the study took about 85  hours based on the computational power of the used device (12-core Intel Xeon with 256 GB RAM).

![image](https://user-images.githubusercontent.com/131758702/234266655-bb6c6539-cf3a-45a5-bc14-e05074034d72.png)

The values of interest (surface area, volume etc.) can be found under *Derived values*

![image](https://user-images.githubusercontent.com/131758702/234267655-21954c88-b7b1-4a4b-b4f1-8899b413df30.png)

*-------------------------------*

-Please do not hesitate to contact me if further clarification or assistance is needed!


