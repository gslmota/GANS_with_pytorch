# GANS_with_pytorch
This repository contains codes for generating GANS images on the MNIST and Fashion MNIST datasets.
The projects are separated by folders, with the name of the datasets.

# Contents
``` shell
.
├── Fashion MNIST
│   └── Geração_de_novas_imagens_com_GANs_base_Fashion_MNIST.ipynb
├── img
│   ├── mf1.png
│   ├── mf2.png
│   ├── mf.png
│   ├── mn1.png
│   ├── mn2.png
│   └── mn.png
├── LICENSE
├── MNIST
│   └── Geração_de_novas_imagens_com_GANs.ipynb
├── README.md
└── requirements.txt
```
The **MNIST** folder contains the python codes used in projects.The other folders follow the same pattern.

# Requirements

 * Check the **requirements.txt** file.


# Test

```shell
git clone https://github.com/gslmota/GANS_with_pytorch.git
cd GANS_with_pytorch
pip install -r requirements.txt
```


# Results

### **MNIST**: 
* **Cnn**. This project using simple CNN.

* Epoch 0 

![!MNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mn.png)
* Epoch 40 

![!MNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mn1.png)
* Epoch 100 

![!MNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mn2.png)

### **Fashion MNIST**: 
* **Cnn**. This project using simple CNN.

* Epoch 0

![!FashionMNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mf.png)
* Epoch 40

![!FashionMNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mf1.png)
* Epoch 100

![!FashionMNIST](https://github.com/gslmota/GANS_with_pytorch/blob/main/img/mf2.png)
 