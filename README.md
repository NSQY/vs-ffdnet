# FFDNet
FFDNet: Toward a Fast and Flexible Solution for CNN based Image Denoising

Ported from https://github.com/cszn/FFDNet


## Dependencies
- [NumPy](https://numpy.org/install)
- [PyTorch](https://pytorch.org/get-started), preferably with CUDA. Note that `torchvision` and `torchaudio` are not required and hence can be omitted from the command.
- [VapourSynth](http://www.vapoursynth.com/)


## Installation
Copy `vsffdnet` directory to Python's `site-packages` directory.


## Usage
```python
from vsffdnet import FFDNet

ret = FFDNet(clip)
```

See `__init__.py` for the description of the parameters.
