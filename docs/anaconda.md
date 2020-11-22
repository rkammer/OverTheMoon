# Anaconda
Create Virtual environment
```
    conda create -n moon python=3.7 pandas jupyter seaborn scikit-learn keras tensorflow
```
Activate Environment
```
    conda activate moon
```
Deactivate Environment
```
    // deactivates the current active environment
    conda deactivate
```

Remove Environment
```
    conda remove --name <environment_name> --all
    conda remove --name test_one --all
```

Install Library
```
    conda install <library>
    conda install pandas
    conda install jupyter
```

List installed libraries
```
    conda list
```

Launch Jupyter
```
    // may need to deactivate and reactivate environment befor launch jupyter for the first time
    jupyter notebook
```

Show paths to environments

```
    conda info --envs
```