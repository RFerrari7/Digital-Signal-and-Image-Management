# Digital Signal & Image Management Project

This repository contains a project developed as part of *Digital Signal and Image Management* course of the [Master's degree in Data Science](https://www.unimib.it/graduate/data-science),
University of Milano Bicocca.

# Description

This project aims to apply three digital signal and image management techniques:

* **Mono-Dimensional signal classification**: using cough recordings as input data, the objective is to develop a multi-class classification model capable of classifying
                                              recordings by subject’s status with comparable or better results than expert physician.

* **Bi-Dimensional signal classification**: using x-ray brain tumor images as input data, the objective is to develop a multi-class classification model capable of classifying
                                            x-ray images and potentially detect different types of brain tumor.

* **DCGAN**: using a dataset containing celebrity faces, the objective is to develop a Generative Adversarial Network (GAN), that can generate completely new images that do not
              exist by learning from the input data with the implementation of neural networks. In this case study, a Deep Convolutional GAN has been developed,
              which can better capture local structures in images.


# Repository structure

This repository is structured as follows:

```
.
├── DSIM Project
│   ├── DCGAN - Roberto Ferrari
│   │   └── DCGAN.ipynb                       # DCGAN task notebook
│   ├── DSIM presentation.pdf
│   ├── bi_dim_signal - Doghmi Samir          # Bi-Dim signal notebook
│   │   └── task_2.ipynb
│   └── mono_dim_signal - Luca Iarocci        # Mono-Dim signal notebook
│       └── COUGHVID_classification.ipynb
└── README.md

```


