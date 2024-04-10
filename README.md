This is a lite version of the transport modelling framework quetzal https://github.com/systragroup/quetzal

Due to persistant installation issues of the entire modelling suite, this version focuses on the most important funtions in order to cease dependencies that are not urgently required. Hence, it ceases the following functionality:
* GPS data integration
* Integrated plotting functions
* Strategy evaluation functions

In detail:
* Function suites erased: Optimal model, Cube model, Connectionscan model, Doc model, Plot model
* Analysis modules erased: cost-benefit analysis, on-demand analysis
* Road pathfinder multitasking via ray and numba