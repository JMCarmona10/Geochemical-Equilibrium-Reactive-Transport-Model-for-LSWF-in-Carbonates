## Code Info 

Complete implementation of the coupled flow, transport, and chemical equilibrium model developed in my doctoral thesis as an oil recovery diagnostic tool for Low-Salinity Waterflooding (LSWF) in carbonate rocks at core scale.

The model couples three physical/chemical phenomena — two-phase flow, multicomponent transport, and local chemical equilibrium — through a Sequential Non-Iterative Approach (SNIA). The Bond Product Sum (BPS) is used as the interpolation variable for relative permeability, serving as a qualitative indicator of wettability alteration and capturing the surface complexation mechanisms more accurately than ionic strength.


⚠️ Important notes before you use this code
1. The data in this repository is synthetic.
The code has been deliberately modified to use made-up data in order to avoid publishing confidential experimental data from experiments. The code works as written, but the numerical values, brine compositions, and reported results here are not the experimental datasets used in the thesis. Do not use these numbers as a reference for real carbonate systems.

2. A custom thermodynamic database is required.
The LSWF-specific geochemical calculations depend on a custom thermodynamic database built during this work (oil surface properties, carbonate surface complexation reactions, and COBR interaction parameters). It is not included in this repository. Standard PHREEQC databases will run the code but will not produce meaningful LSWF results. Contact me to request access to the database.
