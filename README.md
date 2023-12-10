#### COMP6321- Group L

## Description
The project is twofold. Task 1 aims to train VGG11 architectures on NCT-CRC-HE-100K dataset, once trainnig it from scratch and once using a pretrained VGG11 with fine tuning. We also optimize hyperparameters through grid search, and compare the performance of 2 models.In Task 2, the top-performing model of Task 1 (we call it VGG11-I) is used as an encoder for feature extraction on two distincts datasets: Digital Pathology and Artifacts and Animal Faces-HQ. t-SNE dimensionality reduction is then applied on top and finally, classification using supervised KNN and SVN.

The files are in ipynb format, with each file providing a content description at the beginning. Typically, you only need to install the libraries specified at the start of the files and execute the code to perform training and testing.

For Task 1, the intuitive way to follow the code, is to open the files in this order: <br> **1)** from-scratch-training VGG11 and grid search <br> **2)** from-scratch VGG11 + good hyperparameters + normalization <br> **3)** t-SNE on top of from-scratch best VGG11 model <br> **4)** VGG11 with transfer learning <br> **5**) t-SNE on top of the pretrained VGG11 <br> <br> 
For Task 2, the files are independant, you install the libraries used in the first cell of each file, and you run the rest of the cells in the same order. The files names are also self-explanatory.



## Datasets links
NCT-CRC-HE-100K: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0NOZvxl0TPAUxmig?e=K0TpeX) <br>
Digital Pathology and Artifacts:  [link](https://1drv.ms/u/s!AilzKc-njjP7mN0M_LjB5xeAydDsrA?e=0obzsx) <br>
Animal Faces-HQ: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0LqoRZvUYONY9sbQ?e=wxWbip)
