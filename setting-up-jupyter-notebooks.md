### Setting up Jupyter Notebooks
Python, as with nearly all other libraries, takes some time setting up your "IDE" (Integrated Development Environment) and for Data Science and for beginners learning Jupyter Notebooks is the standard. 

That said there takes some effort in creating `conda` environments that are able to be used within the Notebooks. The environments manager a group of packages which are either installed via `conda install <your-package>` or `pip install <your-package>`. Here's how to make sure each conda environment you create is available to you within the Jupyter Notebooks "kernel" menu.

Within any environments you create you will need to install `nb_conda_kernels
```bash
conda install nb_conda_kernels
```

If you have unwanted kernels:
```bash
 # shows your kernels
jupyter kernelspec list

# uninstall the desired kernel
jupyter kernelspec uninstall <kernel_name>
```

If you want a "pretty" display name of your kernel instead of say `conda env:py35` you need to do this within your conda environment:
```bash
python -m ipykernel install --name <disaply_name>

# example
python -m ipykernel install --name python3.5
```



