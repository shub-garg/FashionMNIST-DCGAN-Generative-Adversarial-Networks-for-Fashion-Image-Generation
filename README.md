# FashionMNIST DCGAN

## Project Overview
This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate realistic images of clothing items using the FashionMNIST dataset.

## Folder Structure
- `FashionMNIST_DCGAN.ipynb`: Contains the complete code and implementation for the DCGAN model, including data preprocessing, model architecture, training loop, and result visualization.
- `Images/`: Directory to store sample generated images during training.

## Setup Instructions

### Prerequisites
Ensure you have Python 3 installed. The project also requires several Python packages which can be installed using the following command:
```bash
pip install -r requirements.txt
```

## Running the Notebook

### Clone the Repository:

```bash
git clone https://github.com/yourusername/FashionMNIST_DCGAN.git
cd FashionMNIST_DCGAN
```

## Launch Jupyter Notebook:

```bash
jupyter notebook FashionMNIST_DCGAN.ipynb
```

## Results and Observations
### Discriminator and Generator Losses:
Discriminator losses gradually increase as it becomes harder to distinguish between real and fake images.
Generator losses decrease as it becomes better at generating realistic images.

## Image Quality Progression:
Epoch 10: Blurry and lacking detail.
Epoch 30: Improved clarity and texture.
Epoch 50: Significant enhancements with detailed and realistic images.

##Sample Generated Images
<p align="center">
  <img src="Image/generated.png" alt="Sample Generated Image">
</p>
##Conclusion
The project successfully demonstrates the ability of a DCGAN to generate realistic images of clothing items from the FashionMNIST dataset. Further training and model refinement can yield even better results.
