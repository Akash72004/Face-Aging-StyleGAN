# Face Aging with StyleGAN

## Introduction

This project demonstrates the use of StyleGAN-based techniques for realistic age progression of facial images. It leverages the SAM (Style-based Age Manipulation) model to transform facial features across different age brackets while preserving the subject's identity. The tool allows users to upload a face image and visualize how that face would look at various stages of aging, all through a web-based interface.

## Real-World Problem

Accurately simulating human aging has practical significance across several domains. Law enforcement agencies require reliable aging software to locate missing persons after years, while the entertainment industry and social researchers use age transformation tools to visualize long-term appearance. Traditional image manipulation techniques often fail to maintain identity or produce realistic results. This project addresses that gap using modern GAN-based techniques.

## Application

The tool finds application in facial forensics, media content generation, and longitudinal facial studies. By maintaining key identity features and delivering high-quality age transformations, it can assist in both investigative scenarios and creative projects. Its easy-to-use interface opens it up to use in educational and demonstrative environments as well.

## Methodology

The project utilizes a pre-trained SAM model built on the StyleGAN architecture. Facial images undergo preprocessing, including alignment, resizing, and normalization. These images are encoded into the latent space using a pSp encoder and then manipulated to reflect various age transformations through learned style vectors. The transformed images are then rendered back into photorealistic outputs using the StyleGAN generator. The model pipeline is wrapped in an interactive Gradio interface for seamless user interaction.

Architecture
![Image](https://github.com/user-attachments/assets/e86a6161-87d5-42ac-a567-54b7a7719f54)

Results 
![Image](https://github.com/user-attachments/assets/61ee1f8f-09f9-4140-b538-bca0537b489f)

## Conclusion

The Face Aging with StyleGAN project successfully demonstrates a modern, style-based approach to realistic age transformation. It maintains both image quality and identity through a GAN-driven architecture and delivers a smooth user experience via a web interface. The system holds great potential in forensics, entertainment, and research, with future scope for finer control and mobile deployment.
