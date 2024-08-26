# <a href = "https://github.com/apostovan21/vnncomp2023">German Traffic Signs Recognition Benckmark (GTSRB)</a>

This benchmark set includes 3 binarized neural networks (BNNs), provided in the `onnx/` folder, which were trained using GTSRB. The BNNs contain layers like binarized convolutions, max pooling, batch normalization and fully connected. For the binarized convolution layer we used Larq library [1]. For more details see [2].

The verification properties, provided in the `vnnlib/` folder, represent adversarial robustness to infinity norm perturbations around 0 whose radius of `epsilon` was randomly chosen, see below.

## Dataset details
Although we've tested the model on German/Belgium/Chinese datasets, for verification purpose we suggest starting with German (GTSRB) datatset for testing. As this dataset isn't included in any python package, we have added the test set into `GTSRB_dataset` folder of this repository. 

## ONNX Models
We chose our 3 best models in terms of accuracy, one for each image size we have trained: 30x30, 48x48, 64x64 (px x px). The models can be found in `onnx/` folder.

## VNNLIB Files
We have generated the `vnnlib` files for all three models, with the `epsilon = 1, 3, 5, 10, 15`, and using different `seed = 0`

## Citation
If you find the repo useful, fell free to cite us:

```
@article{postovan2023architecturing,
  title={Architecturing Binarized Neural Networks for Traffic Sign Recognition},
  author={Postovan, Andreea and Era{\c{s}}cu, M{\u{a}}d{\u{a}}lina},
  journal={arXiv preprint arXiv:2303.15005},
  year={2023}
}
```

## References
[1] https://docs.larq.dev/larq/

[2] Andreea Postovan and Mădălina Eraşcu. Architecturing Binarized Neural Networks for Traffic Sign Recognition. https://arxiv.org/abs/2303.15005

### --- List of all traffic_signs_recognition_2023 [conv_net] networks (From :<a href = 'https://github.com/ChristopherBrix/vnncomp2024_benchmarks'> vnncomp2024_benchmarks </a>)---

#### 3_30_30_QConv_16_3_QConv_32_2_Dense_43_ep_30.onnx 
	Number of parameters: 1005587.0 
	Node types: ['Transpose' 'Softmax' 'Sign' 'Conv' 'MatMul' 'Add' 'Reshape']

#### 3_48_48_QConv_32_5_MP_2_BN_QConv_64_5_MP_2_BN_QConv_64_3_BN_Dense_256_BN_Dense_43_ep_30.onnx 
	Number of parameters: 905251.0 
	Node types: ['Reshape' 'Add' 'Softmax' 'MaxPool' 'Sign' 'Conv' 'Mul' 'MatMul' 'BatchNormalization' 'Transpose']

#### 3_64_64_QConv_32_5_MP_2_BN_QConv_64_5_MP_2_BN_QConv_64_3_MP_2_BN_Dense_1024_BN_Dense_43_ep_30.onnx 
	Number of parameters: 1775523.0 
	Node types: ['Reshape' 'Add' 'Softmax' 'MaxPool' 'Sign' 'Conv' 'Mul' 'MatMul' 'BatchNormalization' 'Transpose']