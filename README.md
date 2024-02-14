# Growth stage prediction model -GSP-AI
The main files are as follows:

• Dataset - Wheat growth stage prediction (WGSP) data, manually scored flowering data and the environment data in three field trails.

• Jupyter notebook - Mainly contains the image preprocessing code and the model test code.

• Model save - The results on GSP-AI models for growth stage prediction are saved. 

We also uploaded the UAV data at key growth stage, including orthomosaics images, ground control point files and plot mask. The plot-level images datasets can be analyzed and processed by the AirMeasurer platform [https://github.com/The-Zhou-Lab/UAV-AirMeasurer](https://github.com/The-Zhou-Lab/UAV-AirMeasurer). Then , the image preprocessing code was used to sampling the center part of every plot (1 m2). Finilly the results of wheat growth stage prediction were obtained by GSP-AI.

To install Python, Anaconda and Libraries
If you wish to run from the source code provided in this project, you will need to set up Python on your system.

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/

• To install Anaconda Python distribution:

1) Read the install instruction using the URL: https://docs.continuum.io/anaconda/install

2) For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows

3) An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads

4) We recommend users install the latest Anaconda Python distribution


Some dependencies of the Jupyter notebooks

TensorFlow = 2.2; Scikit-image =0.17; Matplotlib =3.7.1; Pandas=2.0.1; Numpy=1.24.2; Scipy=1.9.1
