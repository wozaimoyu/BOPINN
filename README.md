# BOPINN (Bayesian optimized physics-informed neural network)
PINN is the forward model whereas BOPINN is the inversion scheme which runs BO over PINN to estimate the parameter of the PDE. In BOPINN, a PINN utilizes a neural surrogate to solve the partial differential equation (wave propagation here). Bayesian optimization runs over the PINN model and estimates the optimum parameters (wave velocity in the medium here) using a single snapshot observation of the field.  
For more information:  
1. 
