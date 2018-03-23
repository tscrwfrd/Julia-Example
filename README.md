# Simple-Julia
This repository contains an example Julia implementation of JuMP.


## Installation

1. Install Julia: https://julialang.org/downloads/platform.html
2. Install required packages for Ipopt solver: 
```bash sudo apt-get install build-essential gfortran pkg-config liblapack-dev libblas-dev ```

3. Run julia: 
  - Pkg.init()
  - Pkg.update()
  - Pkg.add("Ipopt") - Julia will compile and install Ipopt
  
### Notes
Ipopt repository: https://github.com/JuliaOpt/Ipopt.jl 

