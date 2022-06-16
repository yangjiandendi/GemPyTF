# GemPyTF
## Overview
This is an TensorFlow extension of [GemPy](https://github.com/cgre-aachen/gempy). 
## Why TensorFlow
GemPy is the most famous Python-based 3-D structural geological modeling open-source software now, which allows the implicit (i.e. automatic) creation of complex geological models from interface and orientation data. We all love GemPy, however, the installation of [Theano](https://en.wikipedia.org/wiki/Theano_(software)) sometime could be frustrating. Therefore this project aims to extend the backend of GemPy with the modern machine learning package [TensorFlow](https://www.tensorflow.org/) for Automatic Differentiation (AD).


## Installation and dependency
The current version is depend on an older version of GemPy-'2.1.1'


## Limitations
At the moment there are only limited models are tested (in [Examples](/Examples/)). 

current version has 
-- no support for topology
-- no support for fault block
-- not been tested with topography

### Known bugs to be fixed
-- 3D color map is in wrong order
-- 2D plot function `show_data` function not correct
