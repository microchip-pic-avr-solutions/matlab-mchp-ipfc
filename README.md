![image](images/microchip.png) 
# MATLAB-Simulink model of Interleaved Boost Power Factor Correction Converter

## 1. INTRODUCTION
This document describes how to configure and run the MATLAB-Simulink model of Interleaved Boost Power Factor Correction Converter.

## 2.	SUGGESTED DEMONSTRATION REQUIREMENTS
### 2.1 MATLAB Model Required for the Demonstration
To clone or download MATLAB model on GitHub,
- Navigate to the [main page of this repository](https://github.com/microchip-pic-avr-solutions/matlab-mchp-ipfc) and
- On the tab <> Code, above the list of files in the right-hand corner, click Code, then from the menu, click Download ZIP or copy the repository URL to clone.

### 2.2	Software Tools Required for the Demonstration
- MATLAB R2022a

## 3.	BASIC DEMONSTRATION
Follow the below instructions step-by-step, to set up and run the MATLAB and Simulink model of Interleaved Boost Power Factor Correction Converter

1. Launch MATLAB R2022a 
2. Open the folder downloaded from the [Github repository](https://github.com/microchip-pic-avr-solutions/matlab-mchp-ipfc)

    <p align="left" >
    <img  src="images/dem1.png">

3. Double-click and open the **IPFC_Mathematicalmodel_MCHP_data.m** file from the folder. This **.m file** contains the configuration parameters required for running the model. Execute the file by clicking the **Run** icon and wait until all the variables are loaded in the **Workspace** tab.

    <p align="left">
      <img  src="images/dem2.png">

4. Double click on the **IPFC_Mathematicalmodel_MCHP.slx** from the folder to open the Simulink model.

    <p align="left">
      <img  src="images/dem3.png">

5. This opens the Simulink model as shown below. Click on the **Run** icon to start the simulation.

    <p align="left">
      <img  src="images/dem4.png">

6. Double click on the **Scope** to view the input and output signals in the system.

    <p align="left">
      <img  src="images/dem10.png">

    Example plots are shown below:
    <p align="left">
      <img  src="images/dem9.png">

    <p align="left">
      <img  src="images/dem8.png"> 

    <p align="left">
      <img  src="images/dem5.png">   

7. **Variable load** subsystem can be used to test the model under different load conditions to check the dynamic performance.

    <p align="left">
      <img  src="images/dem6.png">

8. **Input subsystem** is provided with two input sources ,and it can be used to vary the applied input voltage to the model.
    <p align="left">
      <img  src="images/dem7.png">



