# Instructions
## Installation
The MATLAB toolbox YALMIP is introduced. It is described how YALMIP is be used to model and solve optimization problems for the MPC.

Installation of YALMIP can be done using the YALMIP.m file. Please paste the directory path where the installation must be done in the file

```sh
cd ('enter the path to install');
```

## Execution
The design of MPC is done in main.m file and the LQR and PID is executed in the simulink file PIDnLQR. For the ease of the user the simulink file is called in main.m file. Therefore, the user need to only run the main.m file to reproduce the results. 

## Funtions
1. constraintgen file: Constraints of the optimisation problem is defined in this file.

2. predmodgen file: This file contains the functions related to the state prediction equation.

3. costgen file: The quadratic cost function is implemented in this file.

4. eqcontraintsgen file: The optimization problem that includes the equality constraints corresponding to the desired steady-state of the Propofol concentration .

5. optimalss file: This file represents the Optimal Target Selection (OTS) process.

## License
MATLAB R2021a student license from TU Delft. 



