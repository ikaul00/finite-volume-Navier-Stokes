# finite-volume-Navier-Stokes

This code contains  a  numerical  scheme  to  solve  the  vorticity  formulation  of  the  Navier-Stokesequations  (NSE)  along  with  their  solutions.
The  NSE  is  converted  to  vorticity  evolutions and solved using the Finite Volume method with hyperdiffusion along with Strong Stability Preserving
3rd  order  Runge  Kutta  time  stepping.   
We  present  tests  of  the  1D  case  with constant velocity for a Gaussian and a Gaussian + discontinuous top hat initial conditions 
with some diffusion in the form of viscosity along with periodic boundaries.
Additionally, we  solve  it  in  the  2D  case  for  a  Gaussian  monopole,  and  for  the  vortex  merger  case  (two co-rotating Gaussian monopoles) 
for zero and non-zero viscosity.  
The enstrophy convergence plot is also made for the zero viscosity case and it approaches unity as expected with a rate of 1.8.
