# Computer vision with Jupyter, TensorFlow and Java
Este es el proyecto de la charla de JConf 2022 sobre Computer Vision con Jupyter, Java y Tensorflow.


# Instalacion.

**Necesitaremos el siguiente stack:**

- Anaconda: https://www.anaconda.com
- Java JDK/OpenJDK: https://www.oracle.com/java/technologies/downloads/
- BeakerX kernel: Obtenido por el manejador de paquetes conda en Anaconda.
- TensorFlow Core API Java y TensorFlow framework (instalados via Maven en Jupyter, ver el Jupyter Notebook).

**Instalacion de Anaconda y JDK:**

El proceso de instalacion es sencillo en este caso, solo basta con descargar el ejecutable de ambas aplicaciones, hacer doble clic en el y seguir los pasos de instalacion. Esto aplica para todas las plataformas (Linux, macOS y Windows).

**Instalacion de Jupyter y BeakerX.**

Creamos un conda environment llamado beakerx:

`$ conda create -y -n beakerx 'python>=3'`

Activamos el environment de beakerx de la siguiente manera:

`$ conda activate beakerx`

Notara que el prompt de su terminal cambiara a `(beakerx)$` indicando que se ha cambiado correctamente al environment de beakerx.

Configuramos el environment para que apunte al OpenJDK o JDK que usted tiene en su maquina (en mi caso tengo el JDK v18);

`(beakerx)$ conda config --env --add pinned_packages 'jdk>8.0.121'`.

Instalamos Jupyter y Beakerx:

`(beakerx)$ conda install -y -c conda-forge ipywidgets beakerx`

Para correr jupyter con beakerx:

`(beakerx)$ jupyter notebook`

**Instalando Google Tensorflow desde Maven**

Abrir el jupyter notebook adjunto y seguir las instrucciones en el mismo.
