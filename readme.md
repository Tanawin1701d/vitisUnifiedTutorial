# Hls4ML unified backend tutorial
- This repository introduces you how to use Vitis unified backend to create full flow platform from HLS4ML to pynq zcu102


## envionment install 
1. you can use the conda environment to install its dependency

```bash
conda env create -f environment.yml
conda activate hls4ml-tutorial-dev
```
2. clone the HLS4ML that contains the Vitis Unified backend and install this version in python environment

```bash
git clone https://github.com/Tanawin1701d/hls4ml
cd hls4ml
git checkout  VitisUnifiedClean
pip install -e .
```