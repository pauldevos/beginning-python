### Using SQL in Jupyter Notebooks
The package you're going to need is called [`ipython-sql`](https://github.com/catherinedevlin/ipython-sql) and you can install it with `pip` or [`conda`](https://anaconda.org/conda-forge/ipython-sql).

```bash

conda install -c conda-forge ipython-sql

pip install ipython-sql

# Connection to databaes via SQLAlchemy Connection Strings
# # sqlite://<nohostname>/<path>
%%sql sqlite://
```

A few other useful installs
```bash

conda install nb_conda_kernels ipykernels notebook
```


