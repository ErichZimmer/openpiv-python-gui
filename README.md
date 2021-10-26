# A GUI for Open PIV

OpenPIV-python GUI is a Graphical User Interphase (GUI), providing fast and efficient workflow for evaluating and post-processing particle image velocimetry (PIV) images or results. This repository is based off of [openpiv_tk_gui](https://github.com/OpenPIV/openpiv_tk_gui).
![Screen shot of the GUI showing a vector plot.](https://raw.githubusercontent.com/ErichZimmer/openpiv-python-gui/master/fig/piv_challenge_2014_case_b.JPG)


## Usage <a id=usage></a>

1. Press »File« then »load images«. 
Select some image pairs (Ctrl + Shift for multiple).

2. Click on the links in the image list to view the imported 
images and press »Apply frequencing« to load the images
into the GUI.

3. Walk through the drop-down-menues in »Pre-processing«
and »Analysis« and edit the parameters.

4. Calibrate your images or results with the »Calibration« 
drop-down menu.
       
5. Press the »Analyze all frame(s)« butten to 
start the processing chain. Analyzing the current frame 
saves the correlation matix for further analysis.
    
6. Validate/modify your results with the »Post processing« 
drop-down menu.
    
7. Inspect the results by clicking on the links in the frame-list
on the right.
Use the »Data exploration« drop-down menu for changing
the plot parameters.

8. Re-evaluate images if needed (results are automatically
deleted) with new information/parameters.

9. Export results in ASCI-II


## Documentation <a id=documentation></a>

See wiki


## Related

Also check out [openpiv_tk_gui](https://github.com/OpenPIV/openpiv_tk_gui).