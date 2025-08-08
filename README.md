# NEURAL-STYLE-TRANSFE-1

*COMPANY* : CODTECH IT SOLUTION 

*NAME* : CHANDRESH SINGH BHADORIYA 

*INTERN ID* :CT04DZ609

*DOMAIN*: ARTIFICIAL INTELIGENCE 

*DURATION* : 4 WEEK

*MENTOR* :  NEELA SANTOSH

DESCRIPTION : Neural Style Transfer (NST) is a deep learning technique that blends two images:

A content image (the image you want to keep the structure of)

A style image (the image you want to borrow artistic style from)

The output is a new image that keeps the structure of the content image but painted in the style of the style image.

In Neural Style Transfer (NST), the primary tool used is a Convolutional Neural Network (CNN), especially pre-trained models like VGG19 (a deep CNN architecture developed by Visual Geometry Group, Oxford). NST also utilizes deep learning frameworks such as TensorFlow or PyTorch to implement these models and perform computations.

Summary:
Tool Used: Convolutional Neural Networks (e.g., VGG19), implemented with PyTorch/TensorFlow.

Goal: Merge content of one image with artistic style of another.

Process: Extract features → calculate losses → optimize image iteratively.

Output: A stylized image that artistically resembles the style image while maintaining the structure of the content image.

Neural Style Transfer beautifully showcases the power of deep learning and CNNs in creating AI-generated art.

How it Works :-
Feature Extraction:

A pre-trained CNN like VGG19 is used to extract features from both the content and style images.

The content features are typically taken from deeper layers (they capture shapes and objects).

Style features are taken from multiple layers (they capture textures, patterns, brush strokes).

Loss Calculation:
NST computes three types of loss:

Content Loss: Difference between the content image and the generated image.

Style Loss: Difference in the style (based on Gram matrices) between the style image and the generated image.

Total Variation Loss (optional): To smooth the image and reduce noise.

Optimization:

The generated image (initially a copy of the content image or noise) is iteratively updated using gradient descent.

The goal is to minimize the total loss, i.e., balance content and style.

*OUTPUT 
<img width="243" height="208" alt="image" src="https://github.com/user-attachments/assets/54ce1214-816b-41bc-b7dd-a94407b4a7b3" />

