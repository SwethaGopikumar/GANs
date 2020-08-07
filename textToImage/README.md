# Text To Image Synthesis 


This is an experimental tensorflow implementation of synthesizing images. The images are synthesized using the GAN-CLS Algorithm from the paper [Generative Adversarial Text-to-Image Synthesis][2]. This implementation is built on top of the excellent [DCGAN in Tensorflow][3].


## Datasets
- The model is currently trained on the [flowers dataset][5]. Download the images and save them in ```102flowers/102flowers/*.jpg```.  Also download the captions from [here][6]. Extract the archive, copy the ```text_c10``` folder and paste it in ```102flowers/text_c10/class_*```.  

## Codes
- `downloads.py` download Oxford-102 flower dataset and caption files(run this first).
- `data_loader.py` load data for further processing.
- `train_txt2im.py` train a text to image model.
- `utils.py` helper functions.
- `model.py` models.

## References
- [Generative Adversarial Text-to-Image Synthesis][2] Paper
- [Skip Thought Vectors][1] Paper
- [DCGAN in Tensorflow][3]

[1]:http://arxiv.org/abs/1506.06726
[2]:http://arxiv.org/abs/1605.05396
[3]:https://github.com/zsdonghao/dcgan
[4]:https://github.com/tensorflow/tensorflow
[5]:http://www.robots.ox.ac.uk/~vgg/data/flowers/102/
[6]:https://drive.google.com/file/d/0B0ywwgffWnLLcms2WWJQRFNSWXM/view
