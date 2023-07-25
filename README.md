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
