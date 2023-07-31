# Burgers-PDE-solver-PINN
using a PINN architecture this model approximates the solution u(t,x) of the Burgers differential equation

Burgers equation:
${\displaystyle {\frac {\partial u}{\partial t}}+u{\frac {\partial u}{\partial x}}=\nu {\frac {\partial ^{2}u}{\partial x^{2}}}.}$
# 2d graph output of u(t,x)
v = 0.01/pi

epochs = 100,000

collocation/PDE points = 10000

initial condition + boundary condition points = 100

train time ~ 1 hour on nvidia 1650 ti

final PDE loss = 0.00935 ~ 99.994% accuracy


![image](https://github.com/MasterMeep/Burgers-PDE-solver-PINN/assets/51376656/4ab2212e-400f-44b7-a068-522fd3fbcbd5)
