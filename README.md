# Burgers-PDE-solver-PINN
using a PINN architecture this model approximates the solution u(t,x) of the Burgers differential equation

Burgers equation:
${\displaystyle {\frac {\partial u}{\partial t}}+u{\frac {\partial u}{\partial x}}=\nu {\frac {\partial ^{2}u}{\partial x^{2}}}.}$

# 2d graph output of u(t,x): 99.997% accuracy

v = 0.01/pi

epochs = 10,000 but competitive results at as low as 5,000

collocation/PDE points = 10000

initial condition + boundary condition points = 100

final PDE loss = 0.0046 ~ 99.997% accuracy


![image](https://github.com/MasterMeep/Burgers-PDE-solver-PINN/assets/51376656/f1bc6e28-ee7b-40a3-b2c5-589a5408ad71)

# 3d graph output of u(t,x)

![image](https://github.com/MasterMeep/Burgers-PDE-solver-PINN/assets/51376656/38658b86-3979-45ab-859a-3dce48ecab4a)

![image](https://github.com/MasterMeep/Burgers-PDE-solver-PINN/assets/51376656/fd170c06-da01-42c0-a0e7-09dabba5fe6c)
