# Human Data Analytics Project

The repository contains, under the folder HDA, the functions for the definition of models, the generator used for training, augmentation functions and finally the functions used to display the images. 
The structure of the folder is the following:

```plaintext
HDA/
├── __init__.py
├── models/
│   ├── __init__.py
│   ├── cbam.py
│   ├── Inception.py
│   ├── resnet18.py
├── preprocessing/
│   ├── __init__.py
│   ├── data_augmentation.py
│   ├── image_preprocessing.py
│   ├── image_utils.py
```

The folder training_inference_results/ contains the notebook with the training process and results for each model in a separate notebook and inference-time results in a single notebook for both models.

```plaintext
training_inference_results/
│   ├── Inception_v4_best_model.ipynb
│   ├── ResNet_channel_best_model.ipynb
│   ├── inference_time_results.ipynb
```

The demo.ipynb notebook contains a demo of model at inference-time using an example image and a brief explaination of how inference works.

the pdf file contains the paper that describe the architecture, training and results for bott models.

## Description of Files and Folders

### **Models Folder (`HDA/models/`)**
Definition of the models and the CBAM module in tensor flow:
- `cbam.py`: Contains the definition of the CBAM model.
- `Inception.py`: Contains the definition of the Inception model.
- `resnet18.py`: Contains the definition of the ResNet18 model.

### **Preprocessing Folder (`HDA/preprocessing/`)**
- `data_augmentation.py`: Defines the functions used for data augmentation.
- `image_preprocessing.py`: Contains functions to extract patches and the generator for training.
- `image_utils.py`: Includes helper functions for data preprocessing used in `image_preprocessing.py`.
