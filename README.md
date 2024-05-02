This is a lite version of the transport modelling framework quetzal https://github.com/systragroup/quetzal

Due to persistant installation issues of the entire modelling suite, this version focuses on the most important funtions in order to cease dependencies that are not urgently required. Hence, it ceases the following functionality:
* GPS data integration
* Integrated plotting functions
* Strategy evaluation functions

In detail:
* Function suites erased: Optimal model, Cube model, Connectionscan model, Doc model, Plot model
* Analysis modules erased: cost-benefit analysis, on-demand analysis
* Road pathfinder multitasking via ray and numba

# Installation

Using conda as virtual environment manager is recommendend. In the conda command line, follow these steps:
1. Navigate to the code directory where you want to store this environment and type `git clone https://github.com/marlinarnz/quetzal-lite`
2. Navigate into the new quetzal-lite repository (`cd quetzal-lite`)
3. Create a virtual environment with necessary dependencies (you may specify the name you want behind `-n`): `conda env create -n quetzal -f requirements.yml`
4. Activate the environment: `conda activate quetzal` (or the alternative name you chose)
5. Install this package: `pip install -e .`