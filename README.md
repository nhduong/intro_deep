# Deep Learning Example Programs
Nguyen Hai Duong  
Professor Kim Soo Hyung  
Chonnam National University  
    
## Environment
0. Windows x64
1. Python 3.5
2. TensorFlow
3. Keras v2.0.9
3. CUDA 8.0 (optional, GPU only)
4. cuDNN v5 (optional, GPU only)

## Environment Setup (with GPUs)
0. Check whether you GPU has [Compute Capability 3.0 or higher](https://developer.nvidia.com/cuda-gpus). If not, please refer [Environment Setup (with CPUs)](https://github.com/nhduong/intro_deep#environment-setup-with-cpus)
1. Download and install [CUDA® Toolkit 8.0](https://developer.nvidia.com/cuda-downloads)
2. Download [cuDNN v5.1](https://developer.nvidia.com/cudnn), extract downloaded file, copy `bin`, `include`, and `lib` folders to `%ProgramFiles%\NVIDIA GPU Computing Toolkit\CUDA\v8.0`
3. You should restart your computer to apply system’s changes
4. Download and install [Anaconda 4.2.0 with Python 3.5](https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe)
5. Open Command Prompt as Administrator
6. Install `TensorFlow-GPU` by entering `conda install -c anaconda tensorflow-gpu`
7. Enter `conda install -c anaconda keras-gpu` to install Keras-GPU

## Environment Setup (with CPUs)
1. Download and install [Anaconda 4.2.0 with Python 3.5](https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe)
2. Open Command Prompt as Administrator
3. Install `TensorFlow` by entering `conda install -c conda-forge tensorflow`
4. Enter `conda install -c conda-forge keras` to install Keras

## Usage
1. Download `.ipynb` files to your computer. For example, `D:\dl`
2. Open Command Prompt, type `cd /d D:\dl`
3. Enter `jupyter notebook`
4. `Jupyter IDE` will be opened in a web browser, open one of the downloaded programs
5. Select menu `Cell` > `Run All` to run the program