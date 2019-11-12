# SparkHack

## Setup environment

 * Download `miniconda`: https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe
 * Install in folder: `C:\Users\<my_user>\miniconda3`
 * Create and environment: `conda create -n sparkhack python=3.7.4 jupyter`
 * Access environment: `conda activate sparkhack`
 * install requirements: `conda install --file=requirements.txt`
 * install `findspark`: `conda install -c conda-forge findspark`
 * start notebook: `jupyter notebook`
 * verify installation:
   - open: `python/testing-123.ipynb`
   - run each cell
