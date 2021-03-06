# Normalization Operators

## Batch-Norm
- **Batch Norm**: Sergey Ioffe and Christian Szegedy. Batch normalization: Accelerating deep network training by reducing internal covariate shift. In ICML, 2015.
- Class Conditioned BN:
	- Harm de Vries, Florian Strub, Jeremie Mary, Hugo Larochelle, Olivier Pietquin, and Aaron Courville. Modulating early visual processing by language. NIPS 2017.
- Takeru Miyato, Toshiki Kataoka, Masanori Koyama, and Yuichi Yoshida. **Spectral normalization** for generative adversarial networks. In ICLR, 2018.
- Group Norm

## Layer-Norm

## Weight-Norm
- **Weight Norm**: Tim Salimans and Diederik Kingma. Weight normalization: A simple reparameterization to accelerate training of deep neural networks. In NIPS, 2016.
	- w = g * (v / ||v||)
	- w is scale invariant to v, and the norm is always g
	- Data-dependent initialization (to make output with invariant scales)

## Instance Norm
- Instance Normalization: The Missing Ingredient for Fast Stylization. 2017