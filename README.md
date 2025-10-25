# Data Generation using GAN

## Summary
This project builds a Deep Convolutional Generative Adversarial Network (DCGAN) to generic new, synthetic images. The primary goals is to find the best performing architecture by measuring quality of the gneerated images using Fréchet Inception Distance (FID) score

## Problem
1. Data scarcity: insufficient number of real images to train a robust classification or detection model
2. Data Augmentation: standard augmentation (flips, rotations) is limited, A GAN can create brand-new, realistic images (synthetic data) to build a much larger and diverse training set, leading a better performing AI models

## Methodology
1. Data Loading & Preprocessing
2. Model (generator & discriminator)
3. Evaluation (FID score)
4. Iterative training
   
## Skills
1. Python: Numpy, Matplotlib, OpenCV
2. Deep Learning Frameworks: Tensorflow/Keras
3. Generative Adversarial Networks (GANs): implementing the generator-discriminator architecture)

## Results
1. Created functional GAN capable of generating new images
2. Through iterative experimentation with adjusting model architecture resulting higher epoch didn't instanly giving best results, because the modified 2 model is still outperfomed model with FID Score of 102.41 with lower epoch (200) and batch size (32) for much faster training
   
## Next Steps
1. Analyze the architecture of "modified 2" use it as new baseline for further tuning
2. Implement more GAN training techniques such as WGAN-GP to achieve stable training and lower FID scores
