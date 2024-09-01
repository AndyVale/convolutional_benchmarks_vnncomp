# Cifar2020

**Motivation:** This benchmark combines two convolutional CIFAR-10 networks from last year’s VNN-COMP 2020 with a new, larger network. The goal is to evaluate the progress made in the field of Neural Network verification.

**Networks:** The two ReLU networks, `cifar_10_2_255` and `cifar_10_8_255`, have two convolutional and two fully-connected layers. They were trained for `ℓ∞` perturbations of \(\epsilon = \frac{2}{255}\) and \(\epsilon = \frac{8}{255}\), respectively, using COLT. The larger network, `ConvBig`, has four convolutional and three fully-connected layers and was trained using adversarial training with \(\epsilon = \frac{2}{255}\).

**Specifications:** We draw the first 100 images from the CIFAR-10 test set, rejecting any that are incorrectly classified by the networks. For the remaining images, the specifications describe correct classification under an `ℓ∞`-norm perturbation of at most \(\epsilon = \frac{2}{255}\) and \(\epsilon = \frac{8}{255}\) for `cifar_10_2_255`, `ConvBig`, and `cifar_10_8_255`, respectively. Each sample is allowed a timeout of 5 minutes.

Copied from https://github.com/stanleybak/vnncomp2021

### --- List of all cifar2020 [conv_net] networks (From :<a href = 'https://github.com/ChristopherBrix/vnncomp2022_benchmarks'> vnncomp2022_benchmarks </a>)---

#### cifar10_2_255_simplified.onnx 
	Number of parameters: 2133736 
	Node types: ['Gemm' 'Flatten' 'Conv' 'Relu']

#### cifar10_8_255_simplified.onnx 
	Number of parameters: 2118856 
	Node types: ['Gemm' 'Flatten' 'Conv' 'Relu']

#### convBigRELU__PGD.onnx 
	Number of parameters: 2466858 
	Node types: ['Div' 'Gemm' 'Conv' 'Relu' 'Flatten' 'Sub' 'Constant']

