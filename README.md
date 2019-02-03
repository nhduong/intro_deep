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

## ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) Environment Setup 1 (with GPUs)
0. Check whether you GPU has [Compute Capability 3.0 or higher](https://developer.nvidia.com/cuda-gpus). If not, please refer either [Environment Setup 2 (with GPU Tesla K80 + Google Colab)](https://github.com/nhduong/intro_deep#-environment-setup-2-with-gpu-tesla-k80--google-colab) or [Environment Setup 3 (with CPUs)](https://github.com/nhduong/intro_deep#-environment-setup-3-with-cpus)
1. Download and install [CUDA® Toolkit 8.0](https://developer.nvidia.com/cuda-downloads)
2. Download [cuDNN v5.1](https://developer.nvidia.com/cudnn), extract downloaded file, copy `bin`, `include`, and `lib` folders to `%ProgramFiles%\NVIDIA GPU Computing Toolkit\CUDA\v8.0`
3. You should restart your computer to apply system’s changes
4. Download and install [Anaconda 4.2.0 with Python 3.5](https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe)
5. Open Command Prompt as Administrator
6. Install `TensorFlow-GPU` by entering `conda install -c anaconda tensorflow-gpu`
7. Enter `conda install -c anaconda keras-gpu` to install Keras-GPU

## ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Environment Setup 2 (with GPU Tesla K80 + Google Colab)
A **_free of charge_** way to experience training deep models with high-performance GPU!
1. Visit [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)
2. Sign in with you personal Google account
3. Menu `File` > `New Python 3 notebook`
4. Menu `Runtime` > `Change runtime type` > `Hardware acceleration` > `GPU` > `Save`  
(Note that python source codes will be saved in your Google Drive, and a work shift lasts for 12 hours)  
5. Let's get started with [this Jupyter Notebook](https://github.com/nhduong/intro_deep/blob/master/examples/colab_getting_started.ipynb) (how to use GPU, execute Linux commands, install Python packages, and read data from Google Drive)

## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Environment Setup 3 (with CPUs)
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
