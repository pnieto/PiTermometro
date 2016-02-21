# PiTermometro

## Instalación de dependencias
Instalamos dependencias:
```
sudo apt-get install python-setuptools build-essential python-dev python-pip
sudo pip install virtualenv virtualenvwrapper
```
Configuramos virtualenvwrapper agregando estas lineas al ~/.bashrc:
```
export WORKON_HOME=~/.environments
source /usr/local/bin/virtualenvwrapper.sh
```
Creamos carpeta para venv y cargamos configuracion:
```
mkdir ~/.environments
source ~/.bashrc
```

## Instalación de django
Creamos el venv:
```
mkvirtualenv django
```
Sino se activa el venv automáticamente:
```
workon django
```

Instalación de django:
```
pip install django docutils
```
