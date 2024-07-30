# Flows over Periodic Hills using DDES turbulence models
## A dataset for data-driven turbulence models generated using Delayed Detached Eddy Simulation
***

To train data-driven turbulence models, we need high-fidelity datasets at flow configurations changing continuously with respect to geometrical/physical parameters. In this repository you can find data coming from DDES on a family of geometrically parametrized Periodic Hill (PH) shapes for a total of 25 simulations.

The details on the simualtions are in
* Oberto D., Fransos D. and Berrone S., "Using Delayed Detached Eddy Simulation to create datasets for data-driven turbulence modelling: a periodic hills with parameterized geometry case", submitted

Data are shared as OpenFoam cases. Each case correspond to one geometry. For each case we share:
* the time-and-spanwise averaged velocity and pressure;
* the time-and-spanwise averaged Reynolds stresses.

The RANS results used in the paper have been obtained with a propetary code and are not shared. However, the OpenFoam cases are ready to be runned with the standard OpenFoam $k-\omega$ SST model.

![PH geometry](https://github.com/DavideOberto/PeriodicHills_DDES_dataset/tree/main/para-shapes-our-setting.pdf)

Contacts
* Davide Oberto ([davide.oberto@polito.it](mailto:davide.oberto@polito.it)), Politecnico di Torino
