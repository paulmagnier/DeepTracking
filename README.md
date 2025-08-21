# DeepTracking
This repository contains the code to perform target tracking from marine active acoustic data, as well as a data sample to test it (acquired with a WBAT at the coordinates (12°S, 163°E) in the tropical Pacific). 
To use it, download this repository without changing the locations of files.

# Quick start
0- Requierements:
- Jupyter notebook interpreter
- Matecho software (https://doi.org/10.1007/s40857-018-0135-x), that can be downloaded at https://forge.ird.fr/lemar/active_acoustics/matecho/-/tree/1548a9f753bfa216a580c8252a1a26fb6fd4add3
- The ping rate of your data is < 1 second

1- Open your WBAT data (.raw) in Matecho.
1bis- Alternatively, you can download a data sample from https://doi.org/10.17882/89526

2- If necessary, clean your data.

3- Perform the single target detection in Matecho (Menu SINGLE TARGET DETECTION AND TRACKING).

3- Copy the Cruise directory edited by Matecho to the "data" folder of this project.

4- Run main.ipynb (python) in "Codes" folder.
This code updates the matrix TS.mat in the Cruise directory. This way, you can check the results directly in Matecho.
