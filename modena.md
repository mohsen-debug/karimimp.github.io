## MOdelling of morphology DEvelopment of micro- and NAno Structures, MoDeNa
---

From 2014 to 2017 I was a postdoctoral researcher at [Politecnico di Torino](http://www.disat.polito.it/research/research_groups/musychen/multiscale_modelling_for_materials_science_and_process_engineering) working on MoDeNa project. MoDeNa was a multidiciplinary project that aimed at developing, demonstrating and assessing an easy-to-use multi-scale software-modeling framework under an open-source licensing scheme that delivers models with feasible computational loads for process and product design of polyurethane foams. The main scheme behind MoDeNa was to link different modeling tools developed for nano-, meso-, and macro scales with an uniform platform for simulation of foaming process.



<img src="images/foam_states.png?raw=true"/>



The foam was described as a continuum and the population balance equation (PBE) was applied to determine the evolution of the bubble size distribution (BSD) during the foaming process. The novelty was on-the-fly coupling of the macro-scale model to the other tools derived from different length scales. For example a schematic illustration of communication between macro-scale and meso-scale is shown below. The [MoDeNa repository](https://github.com/MoDeNa-EUProject/MoDeNa) is available online for further info.



<img src="images/connections.png?raw=true"/>



A new [OpenFOAM](https://www.openfoam.com/) solver was also developed which is based on coupling of CFD with PBE. The PBE is solved with quadrature method of moments (QMOM) and the solver accounts for polymerization kinetics, rheology of foam, and foam thermal conductivity. The new solver is labeled as `PUFoam` and for the first time validated for 12 different cases. For more information about the solver you can check out the [PUFoam](https://github.com/karimimp/PUFoam) repository.


<iframe width="560" height="315" src="https://www.youtube.com/embed/hkjpoRFQDLY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

