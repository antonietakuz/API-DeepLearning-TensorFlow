# API-DeepLearning-TensorFlow

Implementaremos una red neuronal usando keras-tensorflow y la ejecutaremos en un servicio web de flask y Streamlit

## 1. Preparación del entorno
    $ conda create -n test anaconda python=3.9.13
    $ conda activate test
    $ conda install ipykernel
    $ python -m ipykernel install --user --name test --display-name "test"
    $ conda install -c anaconda tensorflow-gpu
    $ conda install -c anaconda cudatoolkit
    $ conda install -c conda-forge tensorflow
    $ conda install -c conda-forge/label/broken tensorflow
    $ conda install -c conda-forge/label/cf201901 tensorflow
    $ conda install -c conda-forge/label/cf202003 tensorflow
    $ pip install jupyter
    $ conda install -c conda-forge keras
    $ conda install -c conda-forge/label/broken keras
    $ conda install -c conda-forge/label/cf201901 keras
    $ conda install -c conda-forge/label/cf202003 keras
    $ conda install -c anaconda flask
    $ conda install -c conda-forge streamlit
    $ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]
    
 ## 2. Entrenar la red neuronal
    2.1 Para Falsk
    Descargar el repositorio
    Abrir terminal en la carpeta y correr jupyter notebook
    
    $ jupyter notebook
    
    Ejecutar BirdClass.ipynb
    
    
 ## 3. Probar la red neuronal
 
    $ python TestModel.py
    
## 4. Probar el API de Flask

    $ python app.py
   
 ## 4.1 Probar el API de Streamlit
   
    $ streamlit run appCOVID.py
    $ streamlit run appAves.py
    
    
   

## Agradecimientos

Al trabajo de: 
[DavidReveloLuna](https://github.com/DavidReveloLuna/APIDeep_Streamlit/blob/master/appAves.py)
Canal de Youtube [Click aquì pare ver mi canal de YOUTUBE](https://www.youtube.com/channel/UCr_dJOULDvSXMHA1PSHy2rg)
