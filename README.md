# HEALSwin-PINN
A set of machine learning models for classifying dark matter substructures in gravitational lensing images

## Dataset
Model-1 from DeepLenseSim [GitHub](https://github.com/mwt5345/DeepLenseSim/tree/main)

## Models
- Base Swin Transformer
- Swin Transformer with Relativistic Physics Encoder
- HEAL-Swin
- HEAL-Swin with Relativistic Physics Encoder

## How to use the models
The models are self-contained in Google Colab notebooks. Just edit the data directory to where Model-1 is downloaded in your Drive, and then uncomment the lines that generate the Dataset and Dataloaders. The training and validation dataloaders can be reused for all models.
