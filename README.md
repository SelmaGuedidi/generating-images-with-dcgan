# generating-images-with-dcgan


This GitHub repository contains an implementation of Deep Convolutional Generative Adversarial Networks (DCGAN) for image generation.In this project, we trained the DCGAN model on three diverse datasets: MNIST, Fashion-MNIST, and CelebA to generate stunning and realistic images using the power of deep learning.


## Key Features:


**1-Shared DCGAN Architecture**: Our implementation utilizes the same architecture for both the generator and discriminator networks. This consistent architecture makes it possible to compare test results on different datasets.

**2-Multi-Dataset Training**: We trained the DCGAN model on three popular datasets: MNIST, Fashion-MNIST, and CelebA. This enables the generation of images from different domains, including handwritten digits, fashion items, and celebrity faces, providing a wide range of creative possibilities.

**3-Performance Evaluation**: To assess the quality of the generated images, we employed well-established evaluation metrics: Inception Score and Fréchet Inception Distance (FID). These metrics measure the diversity, realism, and similarity to real images, providing quantitative insights into the performance of the DCGAN model.


**4- Inception Score and FID Calculations**: Our repository will use in-built GAN based metric **PyTorch-Ignite**  to evaluate Frechet Inception Distnace and Inception Score .These calculations will help us objectively evaluate and compare the performance of the DCGAN across different datasets.

See [here](https://pytorch.org/ignite/metrics.html#complete-list-of-metrics) for more details about the implementation of the metrics in **PyTorch-Ignite**.



**5-Visualization and Analysis**: We provide visualizations the generated images during training, allowing you to monitor the progression and quality of the generated images and compare them to the original images from the datasets. You can also analyze the learned representations of the generator and discriminator loss curves and the evolution of the evaluation metrics during training within the DCGAN to gain insights into the underlying image generation process.

**6-Comprehensive Documentation and Examples**: The repository includes detailed documentation, guiding you through the setup, training, evaluation, and fine-tuning of the DCGAN model. We provide clear examples to facilitate a smooth experience while using the codebase.

## Authors:
This project was created by Selma Guedidi, Karim Ellouze and Fatma Hamada for gl3 PPP at INSAT. 

We hope this DCGAN Image Generator repository serves as a valuable resource for exploring the capabilities of generative deep learning and inspires your own experiments in image generation. Enjoy creating stunning images with the power of DCGAN!
