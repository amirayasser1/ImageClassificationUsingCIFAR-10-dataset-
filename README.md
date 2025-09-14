#  CIFAR-10 Image Classification with PyTorch  

<img src="https://miro.medium.com/v2/resize:fit:798/1*rlzLKk9a_9mT1UeXjOvomw.png" alt="cifar" width="500">

This project implements a **Convolutional Neural Network (CNN)** from scratch using **PyTorch** to classify images from the **CIFAR-10 dataset**.  
The dataset contains **60,000 color images (32×32 pixels)** across **10 classes**:  
`airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck`.  

## Key Features
- **Data Preprocessing & Augmentation**
  - Normalization (mean, std of CIFAR-10).  
  - Random crop & horizontal flip.  

- **Model Architecture (SimpleCNN)**
  - 3 convolutional blocks (`Conv2d + BatchNorm + ReLU + MaxPool`).  
  - Classifier: `Flatten → Linear → ReLU → Dropout → Linear`.  

- **Training & Evaluation**
  - Loss: Cross-Entropy.  
  - Optimizer: Adam . 
  - GPU support.  
  - Loss & accuracy curve visualization.  

- **Overfitting Prevention**
  - Data augmentation.  
  - Dropout.  
  - Batch Normalization.  

---

## Results
- Achieved 80% test accuracy
 



