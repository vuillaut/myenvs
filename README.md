# myenvs
Some personal environments (conda, pip, juypter...)

## Add channel to config:
```
conda config --add channels vuillaut
```

## Create new env from conda recipe:
```
conda create -n jlab jlab==1.0
```


## Install kernels in jupyterlab
```
conda activate py36-test
python -m ipykernel install --name py36-test
```
