# beyond_RECIST

# Beyond RECIST: mathematical modeling and Bayesian inference reveals immune parameters predict site specific response in metastatic breast cancer

### Citation
If you use beyond_RECIST in your research, please cite the preprint [here](https://doi.org/10.1038/s41467-024-54711-2).

J Kreger, E Gonzalez, ET Roussos Torres, AL MacLean (2025).
Beyond RECIST: mathematical modeling and Bayesian inference reveals immune parameters predict site specific response in metastatic breast cancer. Preprint.

The bioRxiv version is available [here](https://doi.org/10.1101/2024.03.02.583106). 

### Overview 
This repository contains code used in the mathematical modeling and Bayesian inference of site specific response in metastatic breast cancer. The code is written in Julia (tested on version 1.8.5) and is presented in Jupyter notebooks.

Data used in the analysis is included in the data folder, see the main text for details.

### Requirements 
 - Julia (version 1.8.5)
 - Jupyter notebook

### Package requirements 
 - [DifferentialEquations.jl](https://docs.sciml.ai/DiffEqDocs/stable/)
 - [Turing.jl](https://turinglang.org/)
 - [MCMCChains.jl](https://turinglang.org/MCMCChains.jl/stable/)
 - [StatsPlots.jl](https://github.com/JuliaPlots/StatsPlots.jl)
 - [Distributions.jl](https://juliastats.org/Distributions.jl/stable/)
 - [NonlinearSolve.jl](https://docs.sciml.ai/NonlinearSolve/stable/)
 - [DecisionTree.jl](https://github.com/JuliaAI/DecisionTree.jl)
 - [Symbolics.jl](https://docs.sciml.ai/Symbolics/stable/)
 - [DataFrames.jl](https://dataframes.juliadata.org/stable/)   
 - [Plots.jl; pyplot()](https://docs.juliaplots.org/stable/)
 - [Random.jl](https://docs.julialang.org/en/v1/stdlib/Random/)
 - [JLD.jl](https://github.com/JuliaIO/JLD.jl)
 - [FileIO.jl](https://github.com/JuliaIO/FileIO.jl)
 - [CSV.jl](https://csv.juliadata.org/stable/)

### Project contents
 - `README.md` : this file with information about the repository and [paper](https://doi.org/10.1038/s41467-024-54711-2)
 - `data_processing.ipynb` :  Jupyter notebook containing code for basic methylation data processing.
 - `model_simulation.ipynb` :  Jupyter notebook containing code for all model simulations and figures in the paper.
 - `data` : folder for data used in the analysis, see Table 1 in the main text for details (mz = monozygotic twins, dz = dizygotic twins, ur = unrelated individuals).
 - `simulation files` : folder for simulation files used in the analysis (mz = monozygotic twins, dz = dizygotic twins, ur = unrelated individuals). 

### Acknowledgments
We would like to thank all members of the MacLean lab.

### Contributors
<a href="https://github.com/maclean-lab/FMCs_for_HSCs/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=maclean-lab/FMCs_for_HSCs" />
</a>


