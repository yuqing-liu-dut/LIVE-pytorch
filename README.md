# LIVE-pytorch
Towards Layer-wise Image Vectorization

<div align="center">
  <img src="example.png" width="650px" height="300px">
</div>

## Installation
```bash
pip3 install torch torchvision
pip install svgwrite
pip install svgpathtools
pip install cssutils
pip install numba
pip install torch-tools
pip install visdom
pip install scikit-fmm
```
Next, please refer DiffVG to install [pydiffvg](https://github.com/BachiLi/diffvg)


## Run
```bash
python main.py --config config/all.yaml --experiment experiment_8x1 --signature demo1 --target data/demo1.png
```
Please modify the config files to change configurations.
