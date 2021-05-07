# UnDiaParaDar Datathon
Este repositorio es para uso del Datathon de UnDiaParaDar



## Prerequisitos: 

Abrir la Terminal 

Revisar versión de Python y que esté instalado 
copiar el código y pergar en la terminal 
`python --version` 


Con Homebrew para OSX:
https://brew.sh/index_es

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`brew install python3`

`export PATH=/usr/local/share/python:$PATH`

`pip3 install virtualenv virtualenvwrapper`

Setting PATH for Python 3 installed by brew
`
export PATH=/usr/local/share/python:$PATH
`

Configuration for virtualenv

`
export WORKON_HOME=$HOME/.virtualenvs
export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3
export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv
source /usr/local/bin/virtualenvwrapper.sh
`




## Descarga de Python 
Windows https://edgardorl.com/blog/instalar-python-pip-y-virtualenv-en-windows-10/
OSX: https://brew.sh/index_es

### Virtualenvv

Virtualenvv
Revisar version de virtualenv
`which virtualenv`
Revisar version de python3
`which python3`

Crear ambiente virtual 
`virtualenv -p /home/username/opt/python-3.6.2/bin/python3 venv`

Para activar el ambiente
`source venv/bin/activate`

Se verá así:
(venv) [server]$ 

corroborar la versión de python:
(venv) [server]$  `python -V`

Desactivar el ambiente
[server]$ `deactivate`

Eliminar el ambiente
[server]$` rm -rf venv`

## Primeros pasos

### Descargar librerías

seaborn
pandas
numpy
matplotlib
jupyter

`pip install seaborn pandas matplotlib numpy jupyter`

### Instalar Jupyter Notebooks

`ipython kernel install --user --name=.venv`
Run Jupyter
`jupyter notebook`


Abrirá un página del navegador con Jupyter notebooks. 

Para detener el servidor y la terminal

` Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).`


Continuar en el Workshop del laboratorio de Berkley:
https://github.com/dlab-berkeley/visualization-with-python/blob/master/visualization-with-python.ipynb




Créditos y Referencias: 
Virtualenv:
https://help.dreamhost.com/hc/es/articles/115000695551-Instalar-y-usar-virtualenv-con-Python-3


Virtualenv for Windows or Mac OSX:
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

Data Visualization Workshop: 
https://github.com/dlab-berkeley/visualization-with-python/blob/master/visualization-with-python.ipynb

------
Further resources:
Pandas tutorial (how to deal with data):
https://github.com/dlab-berkeley/introduction-to-pandas
https://pandas.pydata.org/pandas-docs/stable/



