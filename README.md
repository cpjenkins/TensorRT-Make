### About
This repo provides a minimal Makefile alternative to the bazel build in [Torch-TensorRT](https://github.com/pytorch/TensorRT.git)

### Usage
1) Copy both setup.py and torch_tensorrt.mk into root of Torch-TensorRT source repo.
2) Build the wheel
```
python setup.py bdist_wheel --make
```
3) Profit.
