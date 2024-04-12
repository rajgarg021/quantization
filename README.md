# quantization
Implementing various quantization techniques for neural networks using PyTorch

#### What is Quantization and why is it important?
Quantization is the process of converting continuous values to discrete set of values using linear/non-linear scaling techniques. 

It refers to techniques for performing computations and storing tensors at lower bit-widths than floating point precision. A quantized model executes some or all of the operations on tensors with integers rather than floating point values. This allows for a more compact model representation and the use of high performance vectorized operations on many hardware platforms. This technique is in particular useful at the inference time since it saves a lot of inference computation cost without sacrificing too much inference accuracies.

#### Resources:
- https://docs.nvidia.com/deeplearning/tensorrt/tensorflow-quantization-toolkit/docs/docs/intro_to_quantization.html
- https://arxiv.org/pdf/2004.09602.pdf
- https://lilianweng.github.io/posts/2023-01-10-inference-optimization/
- https://leimao.github.io/article/Neural-Networks-Quantization/
- https://huggingface.co/docs/optimum/en/concept_guides/quantization
- https://github.com/google/gemmlowp/blob/master/doc/quantization.md