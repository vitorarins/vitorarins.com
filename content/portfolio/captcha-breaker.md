+++
categories = ["machine-learning"]
coders = []
date = 2020-09-12T00:00:00Z
description = "A Tensorflow program to break CAPTCHAs"
github = ["https://github.com/vitorarins/captcha-breaker", "https://github.com/vitorarins/TCC"]
image = "https://res.cloudinary.com/vitorarins/image/upload/v1599906326/tensorflow-logo.svg"
title = "CAPTCHA breaker"
type = "post"
[[tech]]
logo = "https://res.cloudinary.com/vitorarins/image/upload/v1599906326/tensorflow-logo.svg"
name = "Tensorflow"
url = "https://www.tensorflow.org/"
[[tech]]
logo = "https://res.cloudinary.com/vitorarins/image/upload/v1599906550/numpy-logo.svg"
name = "NumPy"
url = "https://numpy.org/"
[[tech]]
logo = "https://res.cloudinary.com/vitorarins/image/upload/v1599906705/python-logo.png"
name = "Python"
url = "https://www.python.org/"

+++
This was the project I made for my final work at college.

# CAPTCHA breaker

This is just an experiment made for a school project.
It works only for a specific kind of CAPTCHA, which you
can find on this website: http://sistemas3.sef.sc.gov.br/sintegra/consulta_empresa_pesquisa.aspx

It's missing some files:

 - the model: `models/sintegra_sc_model.ckpt`
 - the images: `images/`

## Model

To get a model that recognizes CAPTCHAs, you will need to train a Neural
Network using the `captcha_train.py` script.

## Images

To train the model you will need to download a lot of images (about 500k) and
rename all of those images with the correct characters from inside the image.
Then you can split about 85% of those images in the `images/train/` folder
and the rest in the `images/test/` folder.

## The project

If you want to know more about the project and you understand portuguese you
can read about my work: [TCC](https://github.com/vitorarins/tcc).

