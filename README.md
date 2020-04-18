# A-deep-learning-based-surface-defect-inspection-system-using-multi-scale-and-channel-compressed-features

By Jiangxin Yang, Guizhong Fu, Wenbin Zhu, Yanlong Cao, Yanpeng Cao and Michael Ying Yang

The paper is available at  |[`[PDF Download]`](https://ieeexplore.ieee.org/document/9063543)

### Introduction
In this paper, we firstly proposed to incorporate multiple convolutional layers with different kernel sizes to increase the receptive field and to generate multi-scale features. As a result, the proposed model can better handle cluttered background and defects of various sizes. Also, we purposely compress the size of parameters in the newly added convolutional layers for better learning of defect-related features using a limited number of training samples. Evaluated in a newly constructed surface defect dataset (images contain complex structures and defects of various sizes), our proposed model achieves more accurate recognition results compared with the state-of-the-art surface defect classifiers. Moreover, it is a light-weight model and can deliver real-time processing speed (>100fps) on a computer equipped with a single NVIDIA TITAN X Graphics Processing Unit (12G memory).

###  Dataset
The training dataset can be downloaded at:

Google Drive: https://drive.google.com/open?id=16KaVJS5YKrginhFM1Yk9TtnrikokpXGq

Baidu Cloud: https://pan.baidu.com/s/1UiaK1VxM0kKVlTwhj0gauw  Code：8bt4 

### Overall system
<img src="Dataset/framework.bmp" width="100%" height="100%">

### Implementations
This code is based on Caffe. Thanks to the contributors of Caffe.
Caffe: https://github.com/BVLC/caffe

Our Model also uses the pretrain model SqueezeNet-1.0
SqueezeNet: https://github.com/DeepScale/SqueezeNet



### Experimental Results


### Contact
If you have any questions, feel free to contact:
- Guizhong Fu (fuguizhongchina@163.com)
- Yanpeng Cao (caoyp@zju.edu.cn)


### License
Copyright(c) Guizhong Fu and Yanpeng Cao
All rights reserved.
