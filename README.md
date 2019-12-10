# e-AttnGAN

Pytorch implementation for e-AttnGAN 

### Dependencies
python 3.7

Pytorch

In addition, please add the project folder to PYTHONPATH and `pip install` the following packages:
- `python-dateutil`
- `easydict`
- `pandas`
- `torchfile`
- `nltk`
- `scikit-image`


**Data**

Instructions for Fashion Synthesis and FashionGen datasets will be added soon.


**Training**
- Pre-train DAMSM models:
  - For Fashion Synthesis dataset: `python pretrain_DAMSM.py --cfg cfg/DAMSM/fashion_gen.yml --gpu 0`
 
- Train AttnGAN models:
  - For Fashion Synthesis dataset: `python main.py --cfg cfg/fashion_gen.yml --gpu 0`


### Citing e-AttnGAN
If you find e-AttnGAN useful in your research, please consider citing:

```
to-do
```


### Citing AttnGAN
If you find AttnGAN useful in your research, please consider citing:

```
@article{Tao18attngan,
  author    = {Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang, Xiaodong He},
  title     = {AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks},
  Year = {2018},
  booktitle = {{CVPR}}
}
```

**Reference**

- [StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks](https://arxiv.org/abs/1710.10916) [[code]](https://github.com/hanzhanggit/StackGAN-v2)
- [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434) [[code]](https://github.com/carpedm20/DCGAN-tensorflow)
# e-AttnGAN
