# ats-hillslope

Hillslope simulations for Agashashok (Alaska) in ATS. Uploaded files contain setup for north-facing slope.

There is one discontinuous/thin permafrost scenario and one continuous/thick permafrost scenario. The discontinuous scenario is intitialized from a column frozen from the top (down to app. 2 m from the bottom). The continuous permafrost scenario is initialized from a column frozen from the bottom. The first 30 days of climate forcing data is used only for acheving a realistic snow cover distribution (restart from cp_snow_d30.h5). 

hdf-files named "cp_*" are checkpoint/restart files named for scenario ("dispf" for discontinuous/thin permafrost and "conpf" for continuous/thick permafrost) and day ("d30" for day 30). cp_snow_d30.h5 is 
