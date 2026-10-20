
# Beyond RECIST: mathematical modeling and Bayesian inference reveal the importance of immune parameters in metastatic breast cancer

### Citation
If you use beyond_RECIST in your research, please cite the preprint [here](https://doi.org/10.1101/2025.08.11.669777).

J Kreger, E Gonzalez, X Wu, ET Roussos Torres, AL MacLean (2025).
Beyond RECIST: mathematical modeling and Bayesian inference reveal the importance of immune parameters in metastatic breast cancer. Preprint.

The bioRxiv version is available [here](https://doi.org/10.1101/2025.08.11.669777). 

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
 - [KernelDensity.jl](https://github.com/JuliaStats/KernelDensity.jl) 
 - [Plots.jl; pyplot()](https://docs.juliaplots.org/stable/)
 - [Random.jl](https://docs.julialang.org/en/v1/stdlib/Random/)
 - [JLD.jl](https://github.com/JuliaIO/JLD.jl)
 - [FileIO.jl](https://github.com/JuliaIO/FileIO.jl)
 - [CSV.jl](https://csv.juliadata.org/stable/)

### Project contents
 - `README.md` : this file with information about the repository and [paper](https://doi.org/10.1101/2025.08.11.669777)
 - `data` : folder for data used in the analysis and simulations, see the main text for details.
 - `beyond_RECIST.ipynb` :  Jupyter notebook containing code for analysis and plotting.
 - `profile_wise_analysis.ipynb` : Jupyter notebook containing profile-wise analysis code.
 - `data.xlsx` :  data for each of the 55 tumors (minimum two measurements).
 - `IMC_proportions.xlsx` :  table with the proportion of all immune cell types in the IMC data.
 - `table_baseline_vs_final.xlsx` :  table with the basline and final tumor sizes by site.

### Acknowledgments
We would like to thank all members of the MacLean lab.

### Contributors
<a href="https://github.com/maclean-lab/FMCs_for_HSCs/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=maclean-lab/FMCs_for_HSCs" />
</a>


