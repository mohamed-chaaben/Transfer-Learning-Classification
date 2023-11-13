#### COMP6321- Group L

## Description
The project aims to implement the VGG11 model, optimizing hyperparameters through grid search, and compare its performance with a pretrained network. The top-performing model will then be used as an encoder for feature extraction and classification using a mix of supervised and unsupervised techniques on 3 datasets: NCT-CRC-HE-100K, Digital Pathology and Artifacts and Animal Faces-HQ. <br>

The files are in ipynb format, with each file providing a content description at the beginning. Typically, you only need to install the libraries specified at the start of the files and execute the code to perform training and testing.

The intuitive way to follow the code, is to open the files in this order: **1)** from-scratch-training VGG11 and grid search **2)** from-scratch VGG11 + good hyperparameters + normalization **3)** t-SNE on top of from-scratch best VGG11 model **4)** VGG11 with transfer learning **5**) t-SNE on top of the pretrained VGG11
 


## Datasets links
NCT-CRC-HE-100K: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0NOZvxl0TPAUxmig?e=K0TpeX) <br>
Digital Pathology and Artifacts:  [link](https://1drv.ms/u/s!AilzKc-njjP7mN0M_LjB5xeAydDsrA?e=0obzsx) <br>
Animal Faces-HQ: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0LqoRZvUYONY9sbQ?e=wxWbip)
