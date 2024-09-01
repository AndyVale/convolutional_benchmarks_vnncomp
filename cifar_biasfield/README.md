# <a href="https://github.com/pat676/cifar_biasfield_vnncomp2022">cifar_biasfield_vnncomp2022</a>

**Proposed by the VeriNet team.**

**Motivation:** This benchmark focuses on verifying a Cifar-10 network against bias field perturbations. These perturbations are encoded by creating augmented networks with only 16 input parameters; thus, the problem has a significantly lower input dimensionality than many other image-based benchmarks

**Networks:** For each image to be verified, a separate bias field transform network is created, consisting of a fully connected transform layer followed by the Cifar CNN. The Cifar CNN includes convolutional layers followed by ReLUs. Each bias field transform network has 363k parameters and 45k nodes.

**Specifications:** The specification addresses bias field perturbations of the input. The task is reduced into a standard `ℓ∞` specification by encoding the bias field transformation into fully connected layers, which are prepended to the network under consideration. The bias field perturbations used `ε` = 0.06 and a timeout of 5 minutes

### --- List of all cifar_biasfield [conv_net] networks (From :<a href = 'https://github.com/ChristopherBrix/vnncomp2022_benchmarks'> vnncomp2022_benchmarks </a>)---

#### cifar_bias_field_0.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_1.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_10.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_11.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_12.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_13.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_14.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_15.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_16.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_17.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_18.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_19.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_2.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_20.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_21.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_22.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_23.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_24.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_25.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_26.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_27.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_28.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_29.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_3.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_30.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_31.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_32.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_33.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_34.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_35.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_36.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_37.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_38.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_39.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_4.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_40.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_41.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_42.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_43.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_44.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_45.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_46.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_47.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_48.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_49.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_5.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_50.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_51.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_52.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_53.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_54.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_55.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_56.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_57.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_58.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_59.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_6.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_60.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_61.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_62.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_63.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_64.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_65.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_66.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_67.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_68.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_69.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_7.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_70.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_71.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_8.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

#### cifar_bias_field_9.onnx 
	Number of parameters: 363914 
	Node types: ['Gemm' 'Conv' 'Relu' 'Flatten' 'Constant' 'Reshape']

