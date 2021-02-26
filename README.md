# Introduction

**manage to convert molecule images to smiles(like osra)via ImageCaption.pytorch models**

**welcome to join me to cowork! E-mail:fzzfbyx@163.com facebook:Yuxiao Bai (ZJU)**


# Requirements

Python 3
PyTorch 1.3+ (along with torchvision)
cider (already been added as a submodule)
coco-caption (already been added as a submodule) (Remember to follow initialization steps in coco-caption/README.md)
yacs
lmdbdict


# model

**now using resnet101 to extract image features and transformer to generate smiles**


# improvement

**fine tune resnet101 imagenet weights by using molecules to classification**

**train tokenizers to split smiles into words**

**use short smiles to pretrain**

**use self-critical to reinforcement learning**


# performance

**0.4 accuarcy on 80000 test dataset


# advancement

**improve image feature extracting part by concatenating resnet101 and Vit features**

**I found that many smiles mistakes due to some unclosed tokens like (,generate a smiles candidate list and use beam search to find the correct one**


# code

**two jupyter notebook show the pretrain&data_processing_train_evaluate baseline**







