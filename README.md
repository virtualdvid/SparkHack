# SparkHack

## Setup environment

 * Download `miniconda`: https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe
 * Install in folder: `C:\Users\<my_user>\miniconda3`
 * Create and environment: `conda create -n sparkhack python=3.7.4`
 * Access environment: `conda activate sparkhack`
 * install requirements: `conda install --file=requirements.txt`
 * install `findspark`: `conda install -c conda-forge findspark`
 * start notebook: `jupyter notebook`
 * verify installation:
   - open: `python/testing-123.ipynb`
   - run each cell

### Scala - Jupyter
[reference](https://medium.com/@bogdan.cojocar/how-to-run-scala-and-spark-in-the-jupyter-notebook-328a80090b3b)

 * install `spylon-kernel`: `conda install -c conda-forge spylon-kernel`
 * start kernel:  `python -m spylon_kernel install`
 * start notebook (or refresh in browser): `jupyter notebook`
 * On Home `jupyter` explorer go: `New -> spylon-kernel`
 * verify installation:
   - open: `scala/testing-123.ipynb`
   - run each cell
