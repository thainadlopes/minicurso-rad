# Source directory setup

**TODO**

# Setup at Ubuntu 20.04 LTS x64

## Environment setup

Git (**TODO**)
Python (**TODO**)

## Python setup

Python venv **TODO**

## Jupyter setup

Make Jupyter venv **TODO**

# Setup at Windows 10

## Environment setup

Instale o git utilizando o seguinte link:
- https://git-scm.com/

Instale o python utilizando o seguinte link:
- https://docs.conda.io/en/latest/miniconda.html

Para utilizar o profile do Miniconda

- Ir em configurações padrões (`>Preferences: Open Default Settings (JSON)`) e procurar por profiles.windows
- Copiar o trecho do profiles do **Command Prompt**
- Colar o trecho do profiles nas configurações "pessoais" (`>Preferences: Open Settings (JSON)`)
- Modificar o nome do profile para **Command Prompt (Anaconda)**
- Definir o profile padrão **Command Prompt (Anaconda)** através do comando `>Terminal: Select Default Profile`


## Python setup

Para definir um virtual enviroment para os pacotes do Python é necessário rodar esses comandos

```bat
python -m venv venv
.\venv\Scripts\activate
```

Para fazer as instalações dos pacotes, vamos utilizar os seguintes comandos:

```bat
pip install -r dev-requirements.txt
```

## Jupyter setup

Make Jupyter venv **TODO**
