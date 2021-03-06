
Shallow
=======

Deep learning approaches to the M/EEG inverse problem. Shallow allows 
simulation of source space data (i.e., cortical activity) and sensor space data
(i.e., M/EEG recordings), and then uses neural networks to learn the mapping 
between these two spaces. Shallow can iterate over multiple NN architectures 
and parameters (using Keras and config files). The performance can then be
compared against the standard regularized linear techniques that dominate
neuroimaging.

Dependencies
------------

- [keras](https://keras.io)
- [tensorflow](https://www.tensorflow.org)
- [mne-python](https://github.com/mne-tools/mne-python)
- [docopt](https://github.com/docopt/docopt)
- [pydog-ng](https://github.com/pydot/pydog-ng) (for plotting network architectures)
