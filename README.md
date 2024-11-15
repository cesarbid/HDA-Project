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

## Description of Files and Folders

### **Models Folder (`HDA/models/`)**
Definition of the models and the CBAM module in tensor flow:
- `cbam.py`: Contains the definition of the CBAM model.
- `Inception.py`: Contains the definition of the Inception model.
- `resnet18.py`: Contains the definition of the ResNet18 model.

### **Preprocessing Folder (`HDA/preprocessing/`)**
- `data_augmentation.py`: Defines the functions used for data augmentation.
- `image_preprocessing.py`: Contains functions to extract patches and the generator for training.
- `imageutils.py`: Includes helper functions for data preprocessing used in `image_preprocessing.py`.


