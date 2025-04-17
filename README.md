# Thesis Repository

This repository contains all experiments conducted for my BSc thesis, which investigates how a multi-modal approach compares to single-input models in terms of accuracy for skin cancer detection and classification. It also aims to improve existing multi-modal methodologies found in literature.

# Dependencies

All code was developed in a Python environment using Google Colab Pro, with computer vision models trained on a T4 GPU. [Scikit-Learn](https://scikit-learn.org/) and [PyTorch](https://pytorch.org) were used to implement machine and deep learning models. All required libraries are listed at the beginning of each notebook.

# Organisation

- **`Metadata_Predictions`**  
  Contains `.ipynb` files for exploratory data analysis, baseline models, preprocessing steps, and model comparisons focused solely on metadata classification.

- **`Image_Predictions`**  
  Includes `.ipynb` files for baseline image-based models, model comparisons, a fine-tuned DenseNet121 model, and a Swin-Tiny W&B model for dermoscopic image classification.

- **`Multi_Modal_Predictions`**  
  Contains `.ipynb` files for multi-modal experiments. This includes a basic concatenation model (metadata + DenseNet121), progressively more complex fusion methods using the Swin-Tiny W&B model, and versions of models based on recent literature for comparison.

# Datasets

- [PAD-UFES-20](https://data.mendeley.com/datasets/zr7vgbcyr2/1)  
- [ISIC 2019](https://challenge.isic-archive.com/landing/2019/)  
- [HAM10000](https://www.nature.com/articles/sdata2018161)


