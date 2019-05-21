# jupyter-notebooks
A project for testing on-line deployment of jupyter notebooks.

Notebooks are deployed at mybinder.org: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pjmartel/jupyter-notebooks/master)


The file [requirments.txt](./requirements.txt) contains a list of package names 
to be pip installed by mybinder when creating the container
to run the notebook. If the requisites don't change, there
docker container is simply reloaded, and not rebuilt.

**NOTE:** never use the ephemeral links used by mybinder to bookmark
notebooks - they will be delete as soon as the container stops due
to inactivity

Testing qgrid: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pjmartel/jupyter-notebooks/master?filepath=qgrid_test.ipynb)

Direct Linear Plot: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pjmartel/jupyter-notebooks/master?filepath=direct_linear_plot.ipynb)

Linear regression with confidence intervals: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pjmartel/jupyter-notebooks/master?filepath=linear_regression_confidence.ipynb)



