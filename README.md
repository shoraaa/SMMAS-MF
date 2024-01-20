# SMMAS-OMF: An optimized, memory-friendly smoothed max-min ant system approach for solving big instances of NP-Hard problems. 
### Setup:
1. Install miniconda and Intel C++ Compiler.
2. Create miniconda virtual environment:
```bash
conda create -n acotsp
conda install -n acotsp -c conda-forge gcc=11.4.0
conda install -n acotsp -c conda-forge binutils=2.39
```
### Run:
1.
```bash
source ~/intel/oneapi/setvars.sh
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:~/miniconda3/lib
source activate acotsp
```
2.
```bash
cd ~/Dat/SMMAS-MF/
git pull && make clean && make && ./example_run.sh
```
