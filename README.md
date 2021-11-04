# Uformers for image denoising using Google Collab
Nowadays, thanks to computational and technological advances, computer vision has
become an element that can be found in a multitude of daily situations. In addition, the
massive generation of images and videos has motivated many people and institutions
to take an interest in this field in order to be able to process them and extract the
greatest possible benefit from them.

Many of these images can sometimes be affected by factors that alter their
interpretability and quality, such as noise. To avoid a significant loss of information,
computer vision offers a large number of techniques and algorithms that can be used
with excellent results on image denoising.

*Transformers* are one of the most advanced and widely used neural networks applied
to natural language processing. They are based on an algorithm characterized by the
use of attention, which provides a significant amount of information about the context.
This project arises from the lack of studies related to the use of this architecture in
computer vision and with the goal of demonstrating that Transformers can compete
with other leading architectures on image denoising.

One of its variants, the **Uformer** (by <b>Zhendong Wang, <a href='https://vinthony.github.io'>Xiaodong Cun</a>, <a href='https://jianminbao.github.io/'>Jianmin Bao</a> and <a href='http://people.ucas.ac.cn/~jzliu?language=en'>Jianzhuang Liu</a> </b>), was used to study the effectiveness of this algorithm. This model has
been evaluated and trained on one dataset of 48,000 images, and two of 1,600 images
with different resolutions from cell phone photographs and microscopic radiographs.
After analyzing the results, it is concluded that the Uformer is an effective solution for
image denoising and that it can compete with and even surpass the dominant models
in this field.


**Paper**: https://arxiv.org/abs/2106.03106

This repository contains the implementation of the **Uformer** via the *Google Collab* platform and is trained and evaluated with two new datasets.

## Acknowledgement
This code borrows heavily from [Uformer](https://github.com/ZhendongWang6/Uformer).