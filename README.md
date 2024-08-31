# Anisotropy in Transport Properties using Spin Wave Theory

This repository contains the calculations for studying anisotropy in transport properties, specifically electrical conductivity, using spin wave theory applied to the Coqblin-Schrieffer model for angular orbital momentum `l > 0`. These calculations are part of the research conducted for my master's degree dissertation.


## How to Run the Calculations

To run the calculations, you need to use Jupyter Notebook with the IJulia kernel. Please follow the steps below to set up your environment:

1. **Install Jupyter Notebook**: Make sure you have Jupyter Notebook installed. You can find installation instructions on the [Jupyter website](https://jupyter.org/install).

2. **Install the IJulia Kernel**: IJulia is required to run Julia code in Jupyter. You can install it by running the following command in Julia:
   ```julia
   using Pkg
   Pkg.add("IJulia")
   ```

3. **Install Required Libraries**: The following Julia packages are required for the calculations:
   - `WignerD`: Used for Wigner D-matrix calculations. [WignerD Package](https://juliapackages.com/p/wignerd)
   - `SphericalHarmonics`: Used for handling spherical harmonics. [SphericalHarmonics Package](https://juliapackages.com/p/sphericalharmonics)
   - `Cubature`: Used for numerical integration of angular integrals. [Cubature Package](https://juliapackages.com/p/cubature)
   - `Plots`: Used for generating graphs, version 1.40.4. [Plots Package](https://juliapackages.com/p/plots) with `Matplotlib` as the backend.
   - `PythonPlot`: Version 1.0.3. [PythonPlot Package](https://juliapackages.com/p/pythonplot)
   - `LaTeXStrings`: Version 1.3.1. [LaTeXStrings Package](https://juliapackages.com/p/latexstrings)
   - `ProgressMeter`: Version 1.10.0. [ProgressMeter Package](https://juliapackages.com/p/progressmeter)
   - `SQLite`: Version 1.6.1, for data storage. [SQLite Package](https://juliapackages.com/p/sqlite)
   - `DataFrames`: Version 1.6.1, for data processing. [DataFrames Package](https://juliapackages.com/p/dataframes)

   You can install these packages in Julia by running:
   ```julia
   using Pkg
   Pkg.add(["WignerD", "SphericalHarmonics", "Cubature", "Plots", "PythonPlot", "LaTeXStrings", "ProgressMeter", "SQLite", "DataFrames"])
   ```

4. **Run the Notebooks**: Open Jupyter Notebook, navigate to the directory containing the repository files, and open the notebook files to run the calculations.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

This work is part of my master's degree dissertation and has been made possible thanks to the support of my advisor, [Eduardo Miranda](https://orcid.org/0000-0001-8833-1653), and thanks to my university, the State University of Campinas (Unicamp).

This research was supported by a scholarship from the [National Council for Scientific and Technological Development (CNPq) of Brazil](https://www.gov.br/cnpq/pt-br). I would like to express my gratitude to CNPq for their financial support, which made this work possible.
