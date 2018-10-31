# jupyter-notebooks
A project for testing on-line deployment of jupyter notebooks.

Binder address for Jupyter notebooks repository:
https://mybinder.org/v2/gh/pjmartel/jupyter-notebooks/master

The file requirements.txt contains a list of package names 
to be pip installed by mybinder when creating the container
to run the notebook. If the requisites don't change, there
docker container is simply reloaded, and not rebuilt.

NOTE: never use the ephemeral links used by mybinder to bookmark
notebooks - they will be delete as soon as the container stops due
to inactivity


