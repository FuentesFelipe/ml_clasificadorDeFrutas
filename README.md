# ml_clasificadorDeFrutas
Avance del proyecto "Clasificador de frutas" en desarrollo para la asignatura Aprendizaje Automático, Universidad Tecnológica Metropolitana, Santiago 2019.

## Requisitos
Se recominda el uso de conda que incluye la mayoría de los paquetes requeridos como tensorflow y matplotlib.


## WINDOWS

Para agilizar la instalación de los paquetes, ejecuten las siguientes instrucciones en el CMD ( Ejecutar como administrador ):

* $ @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin" 

* $ choco install python3 git wget

* $ python -m pip install --upgrade pip

* $ pip install conda

* $ git clone https://github.com/FuentesFelipe/ml_clasificadorDeFrutas

* $ cd ml_clasificadorDeFrutas

* $ start https://drive.google.com/file/d/1L1wn9v_9dVeaANEpuXXGFY8zXAAA5yVr/view?usp=sharing

Descomprima el archico en la carpeta ml_clasificadorDeFrutas de manera que la carpeta 'dataset' quede al mismo nivel del echo archivo ML_Images.ipynb.

* Se recomienda ejecutar en un entorno virtual como conda utilizando además jupyter notebook.

## LINUX 

#### Puede simplemente descargar el scripts.rar y ejecutar linux.sh para preparar todo.

* Descomprimir script.zip

* bash ./linux.sh

#### O bien, puede seguir los pasos manualmente:

* $ sudo apt update && sudo apt upgrade

* $ sudo apt-get install python3 rar

* $ pip3 install conda

* $ wget https://raw.githubusercontent.com/circulosmeos/gdown.pl/master/gdown.pl chmod +x gdown.pl

* $ git clone https://github.com/FuentesFelipe/ml_clasificadorDeFrutas

* $ cd ml_clasificadorDeFrutas

* $ perl gdown.pl https://drive.google.com/file/d/1L1wn9v_9dVeaANEpuXXGFY8zXAAA5yVr/view?usp=sharing dataset.rar

* $ unrar x dataset.rar

* $ conda create -n ml_env

* $ conda activate ml_env

* $ conda install jupyter notebook tensorflow jupyter notebook tensorflow matplotlib

* $ jupyter notebook


### Sobre el DATASET

* link https://drive.google.com/file/d/1L1wn9v_9dVeaANEpuXXGFY8zXAAA5yVr/view?usp=sharing dataset.rar
