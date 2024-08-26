# <a href="https://github.com/feiyang-cai/cgan_benchmark2023">CGAN benchmark for VNNCOMP 2023</a>

Description
----------------------
This is a benchmark of conditional generative adversarial networks (cGANs) for VNNCOMP 2023.

The objective of this cGAN is to generate camera images that contain a vehicle obstacle located at a specific distance in front of the ego vehicle, where the distance is controlled by the input distance condition.

Here we attach some generated images as well as the architecture of the cGAN (including both generator and discriminator).

<p align="center">
    <img alt="output_images" src="https://github.com/stanleybak/vnncomp2023/assets/29678149/fd6a36fd-42dd-4361-b28f-c485d494c87e">
</p>
<p align="center">    
    <img alt="cgan_architecture" src="https://github.com/stanleybak/vnncomp2023/assets/29678149/51a653bd-dbdd-4944-ab14-23be3370f565">
</p>

The generator takes two inputs: 1) a distance condition (1-d scalar) and 2) a noise vector that controls the environment (4-d vector). The output of the generator is a generated image.

The discriminator takes the generated image as input and outputs two values: 1) a real/fake score (1-d scalar) and 2) a predicted distance (1-d scalar).

For verification, we combine these two components together and set proper verification specifications for input distance, input noise, and predicted distance.

We also offer several different models with varying architectures (CNN and Transformer) and image sizes (32x32, 64x64) to provide a range of difficulty levels.

### --- List of all cgan_2023 [conv_net] networks (From :<a href = 'https://github.com/ChristopherBrix/vnncomp2024_benchmarks'> vnncomp2024_benchmarks </a>)---

#### cGAN_imgSz32_nCh_1.onnx 
	Number of parameters: 529538 
	Node types: ['Gemm' 'Constant' 'Relu' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']

#### cGAN_imgSz32_nCh_1_transposedConvPadding_1.onnx 
	Number of parameters: 538754 
	Node types: ['Gemm' 'Constant' 'Relu' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']

#### cGAN_imgSz32_nCh_3.onnx 
	Number of parameters: 530404 
	Node types: ['Gemm' 'Constant' 'Relu' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']

#### cGAN_imgSz32_nCh_3_nonlinear_activations.onnx 
	Number of parameters: 530410 
	Node types: ['Gemm' 'Relu' 'Sigmoid' 'Tanh' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']

#### cGAN_imgSz32_nCh_3_upsample.onnx 
	Number of parameters: 352368 
	Node types: ['Gemm' 'Upsample' 'Constant' 'Relu' 'Sigmoid' 'Conv' 'BatchNormalization' 'Reshape']

#### cGAN_imgSz64_nCh_1.onnx 
	Number of parameters: 685768 
	Node types: ['Gemm' 'Relu' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']

#### cGAN_imgSz64_nCh_3.onnx 
	Number of parameters: 686346 
	Node types: ['Gemm' 'Relu' 'Conv' 'BatchNormalization' 'ConvTranspose' 'Reshape']
