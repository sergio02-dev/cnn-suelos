# API_DeepLearning

Implementaremos una red neuronal convolucional (CNN) usando keras-tensorflow, un dataset propio de suelos y la ejecutaremos en un servicio web de flask


## 1. Preparación del entorno
    $ conda create -n cnnsuelo anaconda python=3.7.7
    $ conda activate cnnsuelo
    $ conda install ipykernel
    $ python -m ipykernel install --user --name cnnsuelo --display-name "cnnsuelo"
    $ conda install tensorflow-gpu==2.1.0 cudatoolkit=10.1
    $ pip install tensorflow==2.1.0
    $ pip install jupyter
    $ pip install keras==2.3.1
    $ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]
    
 ## 2. Entrenar la red neuronal
 
    Descargar el repositorio
    Abrir terminal en la carpeta y correr jupyter notebook
    
    $ jupyter notebook
    
    Ejecutar CNN_SUELO.ipynb
    
    Probar la red neuronal
    
## 3. Probar el API de Flask

    $ python app.py


## Agradecimientos

Al trabajo de: 
[DavidReveloLuna](https://github.com/DavidReveloLuna/API_DeepLearning)
