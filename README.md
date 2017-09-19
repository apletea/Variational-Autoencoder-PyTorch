# Variational Autoencoder for face image generation in PyTorch
Variational Autoencoder for face image generation implemented with PyTorch, Trained over a combination of CelebA + FaceScrub + JAFFE datasets.

Based on Deep Feature Consistent Variational Autoencoder (https://arxiv.org/abs/1610.00291)

TODO: Add DFC-VAE implementation

Pretrained model available at https://drive.google.com/open?id=0B4y-iigc5IzcTlJfYlJyaF9ndlU

## Results
Original Faces:
<div>
	<img src='imgs/Epoch_28_data.jpg', width="40%">
  <img src='imgs/Epoch_28_recon.jpg', width="40%">
</div>

Reconstructed Faces:
<div>
	<img src='imgs/Epoch_28_recon.jpg', width="40%">
</div>

Linear interpolation between two face images:
<div>
	<img src='imgs/trans.jpg', width="40%">
</div>

Vector arithmatic in latent space:
<div>
	<img src='imgs/vec_math.jpg', width="40%">
</div>
