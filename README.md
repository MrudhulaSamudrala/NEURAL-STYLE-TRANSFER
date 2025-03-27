# NEURAL-STYLE-TRANSFER

**Company**: CODTECH IT SOLUTIONS

**NAME** : SAMUDRALA SAI MRUDHULA

**INTERN ID** : CT120FHK

**DOMAIN** : ARTIFICIAL INTELLIGENCE

**DURATION** : 8 WEEKS

**MENTOR** : NEELA SANTHOSH

## DESCRIPTION
**Project Overview**:
This project implements Neural Style Transfer (NST) using PyTorch, allowing users to transform an image’s artistic style while preserving its content. Inspired by the work of Gatys et al. (2015), Neural Style Transfer applies the style of one image (e.g., a painting) to the content of another image (e.g., a photograph), creating a unique artwork.

The core idea behind NST is to use a pre-trained Convolutional Neural Network (CNN), such as VGG-19, to extract feature representations of images. By optimizing an image to minimize the difference between its content representation and a given content image, while also matching the style representation of a given style image, NST can generate stunning artistic effects.

This project provides an end-to-end implementation using PyTorch, demonstrating how deep learning models can be used for creative applications. Users can experiment with different content and style images, adjusting parameters to achieve their desired artistic output.

**Tools & Libraries Used**
1. PyTorch – A deep learning framework used for implementing the neural network and optimization process.
   
2. Torchvision – Provides pre-trained models (e.g., VGG-19) for extracting feature maps of images.

3. PIL (Python Imaging Library) – Used for image processing and manipulation.

4. Matplotlib – Enables visualization of input and generated images.

5. Copy Module – Helps manage deep copies of model weights and images during optimization.

These tools enable the seamless execution of the Neural Style Transfer algorithm, allowing for flexible experimentation with different styles and content images.

**Applications of Neural Style Transfer**
Neural Style Transfer has numerous applications, including:

1. Art Creation – Allows artists and designers to generate AI-assisted paintings and unique digital artwork.

2. Photo Enhancement – Transforms ordinary images into stunning artistic renditions inspired by famous paintings.

3. Video Style Transfer – Extends the style transfer concept to video frames, creating animated artistic effects.

4. Augmented Reality (AR) Filters – Used in mobile apps to apply real-time artistic filters to live camera feeds.

5. Data Visualization – Enhances visual representation of scientific or business data using creative styling.

6. E-commerce & Advertising – Generates visually appealing product images for digital marketing campaigns.

**How It Works**
The Neural Style Transfer process follows these key steps:

1️. Load and Process Images

The content image (e.g., a eiffel tower) and style image (e.g., Sunset") are loaded and preprocessed.

Images are resized and converted into tensors suitable for PyTorch models.

2. Feature Extraction Using a Pre-trained CNN (VGG-19)

The VGG-19 model, pre-trained on ImageNet, is used to extract content and style features from the images.

Specific layers of the model capture high-level content information and low-level texture/style patterns.

3️. Define the Loss Functions

Content Loss ensures the generated image retains the structure of the original content image.

Style Loss ensures the generated image mimics the textures and patterns of the style image.

A total variation loss is optionally used to reduce noise and improve smoothness.

4️. Optimize the Image

An optimization algorithm (such as Adam or LBFGS) updates the pixels of the generated image.

The loss functions guide the optimization process to balance content and style features.

5️. Generate and Display the Styled Image

The final stylized image is saved and displayed using Matplotlib.

Users can experiment with different images and hyperparameters to achieve custom artistic effects.

## Output :

