# Growth stage prediction model - GSP-AI

Liyan Shen (沈利言) <sup>1</sup>, Jie Dai (戴杰)<sup>1</sup>, Ji Zhou (周济)<sup>1,2*</sup>

The main files are as follows:

(1) Dataset - The Wheat Growth Stage Prediction (WGSP) data, manually scored flowering data and environment datasets in the trilateral field trails in China, UK and US.

(2) Jupyter notebook - Python-based source coce that contains the image pre-processing, the model integration and execution.  

(3) Outputs of the AI model - The GSP-AI model and output results for growth stage prediction. 

We also uploaded the drone data at key growth stage, including orthomosaics images, ground control point files and plot mask. The plot-level images datasets can be segmented by the AirMeasurer platform [https://github.com/The-Zhou-Lab/UAV-AirMeasurer](https://github.com/The-Zhou-Lab/UAV-AirMeasurer). The image pre-processing code was used to sampling the center part of every plot (1 m^2). Finilly the results of wheat growth stage prediction were obtained by GSP-AI.

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
