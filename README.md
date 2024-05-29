## Colorectal Cancer Tissue Segmentation-Unet

This project involves the development and training of a U-Net model for the automated segmentation of colorectal cancer tissues from histological images. The model architecture includes multiple encoding and decoding blocks, skip connections, and a bottleneck layer, which are integral for capturing the complex features in medical images.

Features:
- Model Architecture: Implements a U-Net architecture with customizable depth and number of filters.
- Training and Validation: Includes detailed training and validation phases, with Dice-loss as loss function and Dice Coefficient and Jaccard Coefficient which is tracked over epochs.
- Performance Evaluation: The model's effectiveness is evaluated on a validation dataset with visualizations of the learning curves for training and validation losses.
- Sample Display: Outputs segmented images alongside the original inputs for visual inspection of model performance. Can be found on: [Inference Notebook](https://www.kaggle.com/code/mahdiislam/colorectal-cancer-segmentation-unet-inference)

Implementation Details:
- PyTorch Framework: The project is implemented using PyTorch and Weights & Biases.
- Dynamic Training Configuration: Training parameters such as batch size, learning rate, and number of epochs are configurable.
- Resource Management: Code includes commands for GPU memory management to ensure efficient resource use during training.
