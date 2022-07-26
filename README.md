# DataCon


## Установка виртуального окружения 

```shell
pip install pipenv
```

```shell
pipenv shell
```

```
pipenv install ...
```

После установки pipenv в левом нижнем углу при использовании `vscode` следует выбрать версию интерпретатора, привязанную к проекту

## Requirments

```shell
pip install -r /path/to/requirements.txt
```

## Conda

```shell
 conda create -n myenv python
 conda env list
 conda activate myenv
 conda list
```

# Jupyter

[Обучение Jupyter Notebook](https://youtu.be/7QM7vQxAAzY)

```
docker run -it --rm -p 8888:8888 -v d:\\workspace\\isuct\\cources\\DataCon:/home/jovyan/work jupyter/datascience-notebook
```