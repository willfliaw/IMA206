# Computational Photography / Patch-Based Methods (IMA206) - 2023/2024

## Course Overview

This repository contains materials and resources for the course **IMA206: Computational Photography / Patch-Based Methods**, part of the **Image-Data-Signal** curriculum. The course focuses on advanced methodologies for image restoration and editing, emphasizing patch-based methods and generative neural networks. Additionally, it explores various applications in computational photography, aiming to extend the capabilities of imaging devices through algorithmic means.

### Key Topics:

- Patch-Based Methods: Leveraging self-similarity in local image neighborhoods to enhance image quality.
- Generative Models: Techniques such as Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) for image synthesis and improvement.
- Computational Photography: Algorithmic techniques that surpass the limitations of imaging devices.
- High Dynamic Range (HDR) Imaging: Techniques to enhance image dynamic range.
- Deconvolution: Methods to remove blur from images.
- Inpainting: Techniques to fill missing parts of an image.

## Prerequisites

Students are expected to have:
- Basic knowledge of image processing and computer vision
- Programming experience, particularly in Python

## Course Structure

- Total Hours: 24 hours (16 sessions)
- Credits: 2.5 ECTS
- Evaluation: Assessed through practical projects and graded assignments.

## Instructor

- Professor Loïc Le Folgoc

## Installation and Setup

Some exercises and projects require Python and relevant image processing libraries. You can follow the instructions below to set up your environment using `conda`:

1. Anaconda/Miniconda: Download and install Python with Anaconda or Miniconda from [Conda Official Site](https://docs.conda.io/en/latest/).
2. Image Processing Libraries: Create a new conda environment with the necessary packages:
   ```bash
   conda create -n ima python matplotlib numpy scipy scikit-image ipykernel pandas scikit-learn jupyter tqdm bokeh opencv munkres
   ```
3. Activate the environment:
   ```bash
   conda activate ima
   ```

4. Launch Jupyter Notebook (if required for exercises):
   ```bash
   jupyter notebook
   ```

This will set up the necessary environment for running image processing tasks and exercises for the course.

## How to Contribute

Feel free to contribute to the repository by:
- Submitting pull requests for corrections or improvements.
- Providing additional examples or extending the projects.
