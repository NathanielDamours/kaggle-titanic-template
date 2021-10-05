# Kaggle's Titanic Competition Template

[![image](https://user-images.githubusercontent.com/88633026/130110875-c9d9a092-59d1-4c4c-8c6a-8925d2ce399d.png)](https://www.kaggle.com/c/titanic)

This is a template to tackle the competition the easy way.

- [Kaggle's Titanic Competition Template](#kaggles-titanic-competition-template)
  - [Explore Data with QuickDA](#explore-data-with-quickda)
  - [Create Quick & Easy Baselines](#create-quick--easy-baselines)
  - [Create Custom Transformers and Modify the Pipeline](#create-custom-transformers-and-modify-the-pipeline)
  - [Create New Models and Change Hyperparameters](#create-new-models-and-change-hyperparameters)
  - [Setup the virtual environment](#setup-the-virtual-environment)
    - [References](#references)
    - [Commands of the presentation](#commands-of-the-presentation)
    - [Clone](#clone)
    - [Anaconda](#anaconda)
    - [Venv](#venv)
    - [Jupyter](#jupyter)

> **#_TODO :_**
>
> - French's translation

## Explore Data with QuickDA

![image](https://user-images.githubusercontent.com/88633026/129945057-5cc06bb8-1331-47e9-a2e2-bc2cac0150fc.png)

## Create Quick & Easy Baselines

![image](https://user-images.githubusercontent.com/88633026/129945592-2d60fe43-07fb-4a16-aacb-ecd5cb04f552.png)

## Create Custom Transformers and Modify the Pipeline

![image](https://user-images.githubusercontent.com/88633026/129948410-92c82bff-4607-49e7-bfdb-e278771a352a.png)

## Create New Models and Change Hyperparameters

![image](https://user-images.githubusercontent.com/88633026/129946210-506e9cfe-11d0-43cd-afc0-ec0d217854c5.png)


## Setup the virtual environment

### References

- [Anaconda install](https://www.anaconda.com/products/individual)
- [Anaconda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- [Anaconda find env path](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/python-path/)
- [PyCharm](https://www.jetbrains.com/lp/pycharm-anaconda/?=)
- [Conda env on PyCharm](https://docs.anaconda.com/anaconda/user-guide/tasks/pycharm/)
- [Jupyter Notebook](https://test-jupyter.readthedocs.io/en/latest/install.html)

### Commands of the presentation

```
git clone https://github.com/NathanielDamours/kaggle-titanic-template.git

# Conda

conda deactivate

conda env create --file conda_requirements.yml

conda activate env_cia_titanic

jupyter notebook

# Venv

python3 - m venv env 

. env/bin/activate

python3 - m pip3 install -r requirements.txt

# Jupyter

jupyter notebook

```

### Clone

```
git clone https://github.com/NathanielDamours/kaggle-titanic-template.git
```

### Anaconda

> ==Deactivate conda's environment==
> ```
> conda deactivate
> ```

> ==Remove conda env==
> ```
> conda env remove -n ENV_NAME
> ```

```
conda create --name NAME python=3.x

conda activate NAME

where/which python

conda install pip

pip install -r requirements.txt

conda list

jupyter notebook
```

### Venv

> ==Deactivate venv==
> ```
> deactivate
> ```

> ==Activate venv==
> 
> Mac
> ```
> . NAME/bin/activate
> ```
> 
> Linux
> ```
> NAME/bin/activate
> ```
> 
> Windows
> ```
> NAME\Scripts\activate
> ```

```  
python -V

python3 -V

python3 - m pip3 install --upgrade pip3

python3 - m venv NAME 

. NAME/bin/activate

python3 - m pip3 install -r requirements.txt

```

### Jupyter

Launch the notebook
``` 
jupyter notebook
```
