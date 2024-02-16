# Detection of Chemio-Physical Properties and Classification of Absorbing Aerosols with the SP2 via a Variational Autoencoder (VAE)
Aaryan Doshi

## Project Summary
This work proposes an unsupervised deep learning method, a variational autoencoder (VAE), applied directly to raw L-II signals from the SP2 in order to classify absorbing aerosols. The VAE compresses L-II signals into a bottleneck latent representation by reconstructing an output similar to the input signal, while maximizing separability of aerosol classes. This method would allow us to easily detect dangerous atmospheric anomalies, generate new training samples from cluster latents, and enable cluster-based label propagation. This work successfully detects and classifies properties of harmful chemical compounds, providing a scalable way to gain much-needed insight into mitigating atmospheric aerosol contribution to global emissions. 

## Code Structure
The VAE.ipynb shows the final variational autoencoder implementation with the tuned hyperparameters used to achieve the results in the paper. Towards transparency and reproducibility, the repository contains the code used for data visualization and preprocessing. In addition, I have included the code for methods that I explored prior to the variational autoencoder. All of the code can be found in their respective directories above. 
