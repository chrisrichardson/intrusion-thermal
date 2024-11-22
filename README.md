# Thermal intrusion modelling

## Model

The code models the symmetric one-dimensional cooling of an igneous intrusion, modelled with the equation:

$$ \rho Cp {dT\over dt} + L {d\phi\over dt} = k {d^2T\over dx^2} $$

where we assume that the melting depends only on temperature, so that we can simplify to:

$$ \left[ \rho Cp + L {d\phi\over dT} \right] {dT\over dt} =  k {d^2T\over dx^2} $$

which is solved using a backward Euler method.

## How to use the code

You can adjust some of the parameters, such as:

* `w` - initial width
* `T0` - initial temperature
* `Tinf` - background (country rock) temperature
* `dt_years` timestep
* `n` and `nw` - the number of points in the discretisation 


