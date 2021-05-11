# Three-phase-inverter-DSP-TMS320F28335

This code was created for my thesis research

Topology:<br />
Three phase VSI<br />
LCL Filter<br />
Grid connected<br />


Abstract

This work investigates the possibility of using the energy stored in the active elements of a static power converter that transfers power from solar panels to the grid for auxiliary purposes. In particular, its propose the option of using the energy of the DC-Link capacitor to obtain more power than the solar panel can generate by itself. At cost of leaving the optimum point of maximum generation of the plant and this way to contribute with more energy to the network when it requires it for short intervals of time.

For this it is obtained the formulas that model the behavior of a solar panel, as a function of solar radiation and ambient temperature, a voltage source inverter and a LCL filter at the output. To determine the parameters is used the MathCad calculation program, is established all the equations according to input parameters in this way it can be obtained the dimensions of the components for different situations.

In addition, a control algorithm is presented capable of operating in two situations. The first is when the system is in normal mode, i.e. when the power consumed in the network is equal to or less than the maximum power generated by the photovoltaic panel. The second situation occurs when the power required by the grid is greater than the PV panel can generate.

The models are verified by Psim simulations in open and closed loop, with emphasis on the dynamics of the response and its stability. The results are verified by experimental tests carried out in the laboratory, using the components available in this laboratory.

The results show that it is possible to provide this energy, while the time during which it can be supplied depends on the size of the capacitor and the amount of energy needed.

You can find further information here:
https://sites.google.com/view/pablovela/solar-energy/thesis-research
