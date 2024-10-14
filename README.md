Este trabajo presenta el desarrollo y entrenamiento de un modelo de red neuronal convolucional (CNN) para la detección automatizada de eventos de lente gravitacional en imágenes astronómicas artificiales.

Se generaron 5500 imágenes de galaxias utilizando el software [GalSim](https://github.com/Dvanegass/GalaxySimulator.git) para el entrenamiento de la red. Debido al tamaño de las imágenes generadas, no es posible añadirlas a este repositorio. En su lugar, se pone a disposición el script GeneraciónImágenesGalSim.py con el cual se crearon las imágenes usando el software GalSim. Este script crea un directorio nuevo para cada perfil de masa utilizado como lente.

Con el script ImagenesLentesGravitacionales.ipynb se reunen todas las imágenes generadas anteriormente en un solo archivo .py que permita utilizarse en los scripts RedNeuronalOriginal.ipynb y CódigoRedNeuronal.ipynb.

RedNeuronalOriginal.ipynb es el script original presentado en la tesis con el que se consiguió el Modelo74%.keras. CódigoRedNeuronal.ipynb es la continuación de este trabajo en miras de conseguir una mejor precisión.
