# Non-Local Neural Networks
["Non-local Neural Networks"(CVPR 2018)](https://arxiv.org/abs/1711.07971)

## Environment

* Keras based implementation, using tensorflow backend.



## Usage
The script `non_local.py` contains a single function : `non_local_block` which takes in an input tensor and wraps a non-local block around it.

## Basic block
- Support for `"Gaussian"`, `"Embedded Gaussian"` and `"Dot"` instantiations of the Non-Local block. 
- Support for variable shielded computation mode (reduces computation by N**2 x, where N is default to 2)
- Support for `"Concatenation"` instantiation will be supported when authors release their code.

From the paper, a basic Non-Local block looks like below (with the Embedded Gaussian instantiation)

<img src="https://github.com/titu1994/keras-non-local-nets/blob/master/images/non-local-block.PNG?raw=true" width=100% height=100%>
