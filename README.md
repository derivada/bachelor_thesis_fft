## La Transformada Rápida de Fourier - Código Fuente
Todo el código se encuentra en formato de notebooks de Python, para la facilidad de su ejecución por partes. Es necesario instalar las librerías necesarias (numpy, scikit-learn, seaborn, matplotlib, ...) y configurar un entorno apropiadamente para ejecutarlos.

#### Procesamiento de señales
Bajo el directorio `audio` se encuentran los archivos necesarios para ejecutar la parte de procesamiento de señales, en la que se filtra una nota de guitarra de una de piano mediante un filtro de paso de banda basado en la convolución acíclica.

### JPEG
Bajo el directorio `jpeg` se encuentran los archivos necesarios para ejecutar la parte de compresón de imágenes con JPEG. En el fichero fuente, se visualiza cada uno de los pasos realizados por JPEG. No incluimos la codificación entrópica.

#### Otros archivos:
- `conv.ipynb` visualización básica de las convoluciones
- `dft_1d.ipynb` visualización básica de la DFT 1-dimensional
- `dft_2d.ipynb` visualización de la DFT 2-bidimensional en 2 dimensiones, junto a plot 3 dimensional cuando se conoce la transformada de la función a aproximar

## The Fast Fourier Transform - Source Code
All source code is found in Python notebook format, for ease of execution and analysis. It is necessary to install some libraries (numpy, scikit-learn, seaborn, matplotlib, ...) and configure an appropiate environment before execution.

#### Signal Processing
Under the `audio` subfolder, all files necessary for execution the signal processing examples are found. We filter a guitar note over a piano with a multi-band bandpass filter using acyclic convolution.

### JPEG
Under the `jpeg` subfolder, we find all the fils necessary for execution of the JPEG compression examples and plots. In the main source file, we visualize each of the steps necessary for JPEF compression (block extraction and DCT encoding + zig-zag). Entropy encoding is not included.

#### Other files:
- `conv.ipynb` basic convolution visualization
- `dft_1d.ipynb` basic 1-d DFT visualization
- `dft_2d.ipynb` visualization of 2-d DFT, with a 3d plot of the continuous transform when the Fourier Transform of the function to approximate via DFT is known