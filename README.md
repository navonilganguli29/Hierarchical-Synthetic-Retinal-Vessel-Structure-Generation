Hierarchical Synthetic Retinal Vessel Structure Generation

Project Overview

This project focuses on the generation of synthetic retinal vessel structures using Generative Adversarial Networks (GANs). The objective is to generate realistic retinal vessel images that can help address the limited availability of annotated retinal datasets for medical image analysis and research.

Objective

The main objective of the project is to develop a GAN-based framework capable of generating anatomically realistic synthetic retinal vessel structures while preserving important characteristics such as vessel connectivity, branching patterns, and hierarchical vessel structures.

Datasets

The project uses publicly available retinal image datasets, including:

* DRIVE
* STARE
* CHASE_DB1
* HRF

These datasets provide retinal fundus images and vessel-related information used for training and evaluation.

Methodology

The project follows a GAN-based approach consisting primarily of a **Generator** and a **Discriminator**.

The Generator learns to produce synthetic retinal vessel structures, while the Discriminator evaluates whether the generated samples resemble real retinal vessel structures.

The overall workflow includes:

1. Dataset collection and preparation
2. Image preprocessing and resizing
3. Training the GAN model
4. Generation of synthetic retinal vessel structures
5. Evaluation of generated samples
6. Comparison with real retinal vessel structures

Technologies Used

* Python
* PyTorch
* Deep Learning
* Generative Adversarial Networks (GANs)
* Computer Vision
* Image Processing

Evaluation

The generated images were evaluated using image-quality and similarity metrics such as:

* Fréchet Inception Distance (FID)
* Structural Similarity Index (SSIM)
* Peak Signal-to-Noise Ratio (PSNR)
* Learned Perceptual Image Patch Similarity (LPIPS)

These metrics were used to assess the quality and similarity of the generated retinal vessel structures.

Applications

Synthetic retinal vessel generation can potentially support:

* Medical image analysis
* Retinal vessel segmentation research
* Dataset augmentation
* Deep learning model development
* Research on retinal disease analysis

Project Outcome

The project demonstrates the application of GAN-based deep learning techniques for generating synthetic retinal vessel structures and explores the potential of synthetic data to supplement limited medical imaging datasets.

Project Presentation

The complete final-year project presentation is available in this repository:

**Final Year Project PPT.pdf**


# Hierarchical-Synthetic-Retinal-Vessel-Structure-Generation
