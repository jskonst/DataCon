# DataCon


## Установка виртуального окружения 

```shell
pip install pipenv
```

```
pipenv shell
```

После установки pipenv в левом нижнем углу при использовании `vscode` следует выбрать версию интерпретатора, привязанную к проекту

## Conda

```shell
 conda create -n myenv python
 conda env list
 conda activate myenv
 conda list
```

# Jupyter

docker run -it --rm -p 8888:8888 -v d:\\workspace\\isuct\\cources\\DataCon:/home/jovyan/work jupyter/datascience-notebook
