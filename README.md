# Physics-Informed Neural Network (PINN) for 1D Diffusion Equation

## Overview
This repository implements a **Physics-Informed Neural Network (PINN)** to solve the **1D Diffusion Equation** using PyTorch. PINNs use deep learning to approximate solutions to partial differential equations (PDEs), enforcing both boundary conditions and the governing equation during training.

This code:
- Solves the **1D Diffusion Equation** using a physics-informed neural network.
- Implements **automatic differentiation** to compute PDE residuals.
- Uses **boundary and initial conditions** for supervised learning.
- Supports **Adam and L-BFGS optimizers** for training.
- Provides **visualizations of the learned solution** against the exact solution.

![Img1](https://github.com/user-attachments/assets/e969cad4-423f-4f3e-b07c-fe86c1aca01d)
![Img2](https://github.com/user-attachments/assets/95c3bed3-9649-489f-b9c9-9c7ad35b173e)



## References
Followed [this](http://www.google.frhttps://github.com/jdtoscano94/Learning-Scientific_Machine_Learning_Residual_Based_Attention_PINNs_PIKANs_DeepONets/ "this") tutorial by Juan Diego Toscano.

## License
This project is licensed under the MIT License. See `LICENSE` for details.


