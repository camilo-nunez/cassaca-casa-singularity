# CASA 6 Container


## Basic Environment
|   |   |
|---|---|
|OS|Rocky 8|
|Python Version|3.8|
|CASA Version|6.5.3|

## Singularity Commands
Build the container image:
```
singularity build --notest container-casa.sif container-casa.def
```


Execute a terminal with the builded image:
```
singularity run container-casa.sif
```


Open a IPython terminal with CASA's libs loaded:
```
singularity run container-casa.sif
```