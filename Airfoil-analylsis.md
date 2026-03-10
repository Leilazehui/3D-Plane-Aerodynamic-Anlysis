# Airfoil Analyais

**Tool**: XFLR5, MATLAB

**2D Airfoil Comparison**
Candidates: MH60, NACA 0009, NACA 0012, SD7037, CLARK Y, Davissm, WORTMANN FX 63-137 (WFX)

<p align="center">
  <img src="https://github.com/Leilazehui/3D-Plane-Aerodynamic-Anlysis/blob/main/Assets/CL-CD-XFLR5.png" width="40%"  />
  <img src="https://github.com/Leilazehui/3D-Plane-Aerodynamic-Anlysis/blob/main/Assets/cl-aoa.png" width="23%"  />
  <img src="https://github.com/Leilazehui/3D-Plane-Aerodynamic-Anlysis/blob/main/Assets/cl-xtr.png" width="20%"  />
</p>


**3D Airfoil Comparison**
Candidates: Hybrid of 65% CLARK Y and 35% WFX; Davissm, Clark Y, WFX

<p align="center">
  <img src="https://github.com/Leilazehui/3D-Plane-Aerodynamic-Anlysis/blob/main/Assets/Coefficient%20of%20Lift-Drag%20Ratio%20vs%20Angle%20of%20Attack.png"  width="40%"  />
  <img src="https://github.com/Leilazehui/3D-Plane-Aerodynamic-Anlysis/blob/main/Assets/Coefficient%20of%20Drag%20vs%20Angle%20of%20Attack.png"  width="45%"  />
</p>

In Xflr5 Aanalysis, the data of CL, CD, CM and other parameters when the angle of the aircraft of 2 is considered. The final lift force with the lift equation: L = rhox*Cl*x*V^2*x*WingArea*1/2 and drag force with the drag equation:D = rho*x*Cd*x*V^2*x*Wingarea*1/2 are computed.

L =  66N
D = 1.2N

While in CFD analysis on Ansys, without the landing gear, the final value for the L and D is:
L = 41N
d = 5.6N
