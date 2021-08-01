# CNN-SINDy-MLROM
Sample codes of CNN-SINDy based reduced-order modeling for fluid flows.  
The present model can derive a governing equation of low-dimensionalizaed manifolds of fluid flows extracted via convolutional neural network-based autoencoder.

# Reference
Kai Fukami (UCLA), Takaaki Murata (Keio), Kai Zhang (Rutgers Univ.), and Koji Fukagata (Keio), "Sparse identification of nonlinear dynamics with low-dimensionalized flow representations," Journal of Fluid Mechanics, accepted, preprint: [arXiv:2010.12177](https://arxiv.org/abs/2010.12177), 2021

# Information
Author: [Kai Fukami](https://scholar.google.co.jp/citations?user=ipJb8qcAAAAJ&hl=en) (UCLA)

This repository contains a sample notebook of SINDy for AE-based latent variables with a periodic cylinder wake.
Authors provide no guarantees for this code. Use as-is and for academic research use only; no commercial use allowed without permission. The code is written for educational clarity and not for speed.
Since this is a sample notebook, we also do not provide a data set and CNN-AE. For the data set and CNN-AE, please refer to our previous papars with [their sample codes](https://sites.google.com/view/kai-fukami/%E3%83%9B%E3%83%BC%E3%83%A0/let-us-machine-learn?authuser=0) as follows:

1. T. Murata, K. Fukami, and K. Fukagata, "[Nonlinear mode decomposition with convolutional neural networks for fluid dynamics](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/abs/nonlinear-mode-decomposition-with-convolutional-neural-networks-for-fluid-dynamics/6F1350060022629E0330FD1D97CE917C)," J. Fluid Mech. 882, A13 (2020).
2. K. Hasegawa, K. Fukami, T. Murata, and K. Fukagata, "[CNN-LSTM based reduced order modeling of two-dimensional unsteady flows around a circular cylinder at different Reynolds numbers](https://iopscience.iop.org/article/10.1088/1873-7005/abb91d)," Fluid Dyn. Res. 52, 065501 (2020).

# Requirements
* Python 3.x  
* keras  
* tensorflow
* sklearn
* numpy
* pandas
