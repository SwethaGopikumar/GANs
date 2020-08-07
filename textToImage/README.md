# Text To Image Synthesis 


This is an experimental tensorflow implementation of synthesizing images. The images are synthesized using the GAN-CLS Algorithm from the paper [Generative Adversarial Text-to-Image Synthesis][2]. This implementation is built on top of the excellent [DCGAN in Tensorflow][3].


## Datasets
- The model is currently trained on the [flowers dataset]. Download the images and save them in ```102flowers/102flowers/*.jpg```. Extract the archive, copy the ```text_c10``` folder and paste it in ```102flowers/text_c10/class_*```.  

## Codes
- `downloads.py` download Oxford-102 flower dataset and caption files(run this first).
- `data_loader.py` load data for further processing.
- `train_txt2im.py` train a text to image model.
- `utils.py` helper functions.
- `model.py` models.

## References
- [Generative Adversarial Text-to-Image Synthesis][2] Paper
- [Generative Adversarial Text-to-Image Synthesis with Skip Thought Vectors](https://github.com/paarthneekhara/text-to-image) TensorFlow code
- [DCGAN in Tensorflow][3]
