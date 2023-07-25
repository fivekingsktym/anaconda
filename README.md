# Creating conda environment

## case-1

```bash
conda.bat create --name env_name
```

```bash
conda.bat activate env_name
```


## case-2

```bash
conda create -m env_name
```

```bash
conda activate env_name

<or>

activate env_name
```

## Creating packages from yml file

```bash
conda env create -f environment.yml
```
#### environment.yml file

```bash
channels:
  -  defaults
dependencies:
  - jupyter
  - pandas
  - matplolib
  - scipy
  - python=3.9
  - pip

```

## Removing the conda env

```bash
conda env create -n env_name
```

## installing package without activating the conda env => eg: C:\Users\ACER>

```bash
conda env create -n env_name python=3.9 jupter pandas django
```

