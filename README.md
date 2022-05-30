# Early-exit-Inference-Weak-Dominance
This is an RnD Project on Early-exit inference of NNs using Online machine learning aspects

## Conda Environment
Requires conda/miniconda for package management.
To set up the environment: 

`conda env create --file pt1_8_env.yaml`

## Other python requirements
installed onnx-1.8.1 

onnxruntime-1.7.0 

protobuf-3.15.5

Can be installed from conda env with:

`pip install onnx onnxruntime`


## Running onnx test script
Should work from environment `pt1_8_env.yaml`

Requires path to trained network for branchynet, not required for testnet/lenet.

Command:
`python main.py`
