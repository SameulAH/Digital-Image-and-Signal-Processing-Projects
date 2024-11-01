# Digital Signal and Image management Projects
In this repository, the project for tthe Digital Signal and Image Management exam is reported. In particular, three main tasks are addressed:

## Image Retrieval
This project (Face Retrieval) integrates transfer learning with the MobileNetV2 architecture to enhance the accuracy and efficiency of facial feature extraction. By leveraging MobileNetV2, a lightweight yet powerful model, the system extracts deep, high-quality feature embeddings from each face. These embeddings are then indexed using a KD-Tree structure, allowing for rapid retrieval of similar faces across various datasets.



## Image Classificatiom

This project classifies food images from the Food-101 dataset, beginning with data cleaning and augmentation techniques like rotation and scaling. Initial experiments involve training CNN models from scratch to establish a baseline accuracy. The project then leverages transfer learning with pre-trained ResNet50 and Inception models, focusing on 51 food classes. Through iterative parameter tuning and augmentation, significant accuracy gains are achieved, with ResNet50 performing best. This workflow demonstrates the effectiveness of combining CNN training with transfer learning for accurate food image classification.



## Audio Claffication

This project tackles music genre classification through two approaches. Initially, an SVM model is trained using basic audio features like Zero-Crossing Rate, song duration, and energy, establishing a performance baseline. Then, a CNN model is employed, leveraging more complex features such as MFCCs, Spectrograms, and Chroma features to capture detailed audio characteristics. Data augmentation further enriches these features, improving model robustness. Experiments with feature combinations and parameter tuning optimize accuracy, creating an effective, multi-faceted system for genre classification.