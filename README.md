# Histology Image Classification with Fractal Features and Deep Learning
This project explores histology image classification by combining handcrafted fractal features with deep learning models. While CNN-based approaches like ResNet-50 are widely used, they often require large datasets and struggle to generalize across different tissue types.

Our approach is an ensemble model that integrates:

- ResNet-50 for image classification,
- Local and global fractal features extracted from histological datasets,
- A sum rule strategy to combine handcrafted and deep learning results.
- Fractal geometry is used to extract handcrafted features. Local features are reshaped into "feature images" and processed by CNNs, while another CNN receives the original histology images. We evaluated four reshaping procedures for local features and combined them with machine learning classifiers.

Results
Achieved 88.45% – 99.77% accuracy across five datasets.
Robust to different image resolutions and imbalanced classes.
Required only a few training epochs.

Conclusion
The proposed ensemble method reaches results comparable to state-of-the-art approaches in histology image classification, showing the effectiveness of combining fractal descriptors with deep learning.

This code is part of the master's thesis "Classification of Oral Cavity Dysplasia Based on Fractal Descriptors and Ensemble Learning" (https://repositorio.ufu.br/handle/123456789/43129)
