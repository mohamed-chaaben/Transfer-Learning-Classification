#Transfer Learning and Feature Extraction Using VGG11 for Medical and Natural Image Classification
This project was completed as part of the COMP 6321 Machine Learning course. The attached PDF (report.pdf) is an IEEE-like paper summarizing the work.

## Description
The project is divided into two tasks:

 - Task 1: We train VGG11 architectures on the NCT-CRC-HE-100K dataset, first from scratch and then using a pretrained VGG11 with fine-tuning. Additionally, hyperparameters are optimized through grid search, and the performance of the two models is compared.
 - Task 2: The top-performing model from Task 1 (referred to as VGG11-I) is used as an encoder for feature extraction on two distinct datasets: Digital Pathology and Artifacts, and Animal Faces-HQ. We then apply t-SNE for dimensionality reduction and perform classification using supervised KNN and SVM.

## Files
The files are provided in Jupyter notebook (`.ipynb`) format, each containing a description of the content at the beginning. The files names are self-descriptive too.
To run the project, simply install the required libraries listed at the start of each notebook and execute the code to perform the training and testing processes.

For Task 1, the intuitive way to follow the code, is to open the files in this order:

 1. `from-scratch-training VGG11 and grid search.ipynb`
 2. `from-scratch VGG11 + good hyperparameters + normalization.ipynb`
 3. `t-SNE on top of from-scratch best VGG11 model.ipynb`
 4. `VGG11 with transfer learning.ipynb`
 5. `t-SNE on top of the pretrained VGG11.ipynb`

For Task 2, the files are independant, their names start with "Task 2 -". All needed is installing the libraries used in the first cell of each file, and then running the rest of the cells in the same order. 



## Datasets links
NCT-CRC-HE-100K: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0NOZvxl0TPAUxmig?e=K0TpeX) <br>
Digital Pathology and Artifacts:  [link](https://1drv.ms/u/s!AilzKc-njjP7mN0M_LjB5xeAydDsrA?e=0obzsx) <br>
Animal Faces-HQ: [link](https://1drv.ms/u/s!AilzKc-njjP7mN0LqoRZvUYONY9sbQ?e=wxWbip)
