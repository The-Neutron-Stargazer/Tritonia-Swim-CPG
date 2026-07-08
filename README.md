This repository was created by me as part of the project titled, "How robust is the Swim CPG of Tritonia?" created and presented at Computational Approaches To Memory and Plasticity (CAMP) 2026, IISER Pune by a team consisting of: 
Darshan R (Krea University)
Shraddha Pathak (TIFR-NCBS) 
Srujana Kaluve (IISER Mohali)
Rittika Dutta (IISER Behrampur)
Sakshi Jethva (IIT Delhi)

The repository consists of the follow files (and a brief description):
- Tritonia_Swim_CPG_Network_main.ipynb : Main notebook file where we replicate a 3-cell swim CPG
- Extraction_of_Data.ipynb : To extract and play around with the extracted data
- Leak.mod : Leak current equations
- Thold.mod : Dynamic threshold values
- Shunt.mod : Time-varying shunt conductance values
- Oldsyn.mod : Three timescale synaptic kernels
- tritonia_cpg.ode : 9-D differential equation of the model

  Run the ipynb files _after_ installing Brian2 on your ODE. Installation guide: https://brian2.readthedocs.io/en/stable/introduction/install.html
