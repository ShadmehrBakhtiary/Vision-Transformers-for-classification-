# Vision-Transformers-for-classification


# Image Classification on MedMNIST Dataset

## Overview
This project implements image classification models to classify two classes from the MedMNIST dataset: **BloodMNIST** and **BreastMNIST**. The classification is performed using two different methodologies: Convolutional Neural Networks (CNN) and Vision Transformers (ViT). The project explores the effectiveness of these models on small-sized datasets while leveraging advanced techniques tailored for performance optimization.

## Datasets
- **BloodMNIST**:  A dataset for classifying blood cell images.
- **BreastMNIST**: A dataset for classifying breast cancer histopathology images.

Both datasets are part of the [MedMNIST](https://medmnist.github.io/) project, which offers a collection of common medical image classification datasets.

## Methodologies
This project employs two primary methodologies for model training:

1. **Convolutional Neural Networks (CNN)**: Implemented as the baseline model to classify the images from the specified datasets.
   
2. **Vision Transformers (ViT)**: Two variations are tested:
   - **Vanila ViT**
   - **Shifted Patch Tockenization with Locality Self Attention (LSA)**: A technique specified for small-sized datasets to improve classification performance.

## Results
- The results show that Vision Transformers outperform CNN models in classification tasks, particularly for the BreastMNIST dataset.
- ![We can observe all results with different models](https://github.com/ShadmehrBakhtiary/Vision-Transformers-for-classification-/blob/main/Screenshot%202024-08-24%20215706.png)
- The Shifted Patch + LSA method yielded the best performance across the models for small datasets tested.



## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- [MedMNIST](https://medmnist.github.io/) for providing the datasets.




