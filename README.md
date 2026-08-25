# Numerical Simulation of Aircraft Attitude 
## 6-DOF simulation with aircraft EOMs

### Items Needed:
MATLAB needed to run the code.  

Main Run File: **Project.m**

See **SCENARIO** Folders for Simulation Results. 

### Scenario 1: 
- Center of Pressure is exactly at Center of Gravity
- Zero changes in attitude (roll, pitch, yaw) graphs

### Scenario 2:
- Center of Pressure (COP) is 1 mm behind the Center of Gravity (COG)
- Healthy take-off, attitude changes, lands on the ground.
- Launch trajectory is mapped

### Scenario 3:
- Center of Pressure (COP) is 1 mm **AHEAD** of Center of Gravity (COG)
- Shows the projectile is spiraling out of control (see roll, pitch, yaw) graphs.

### Try Yourself:

    C.P.Rcpcg = [1; 0; 0] * 1E-6;
    %[km]The position of the center of pressure WRT to the center of gravity.

There are many variables that you can change in this code to experiment with it. 
- Go to **ConstantsP.m**
- Change **COP** location with respect to C.G.
  

  
