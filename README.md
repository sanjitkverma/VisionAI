An AI-powered image detection program that accurately identifies and compares objects within two images. 

Project Overview:
This project aims to explore unsupervised feature learning techniques for image recognition tasks using the CIFAR-10 dataset. The dataset contains 60,000 32x32 color images divided into 10 classes, each with 6,000 images. The project investigates the efficiency and effectiveness of unsupervised learning methods in recognizing various objects within the CIFAR-10 dataset.

Methodology:
- Utilization of a pre-trained VGG16 model for feature extraction.
- Application of the K-means clustering algorithm to group similar images based on the extracted features.

Clustering Process:
The K-means clustering algorithm is executed to categorize the images according to their extracted features. This process aids in identifying common patterns and groupings within the dataset.

Evaluation Metrics:
- Clustering quality is assessed by comparing the results with the ground truth labels.
- The purity score is adopted as a metric to quantify the performance of the clustering algorithm.

Similarity Assessment:
After model training, the cosine similarity metric is integrated to determine the likeness between pairs of images. This metric provides a more meaningful interpretation of feature vector similarity compared to the Euclidean distance used in K-means clustering.

Objectives:
- Explore unsupervised feature learning methods for image recognition.
- Evaluate the efficiency and efficacy of these methods using the CIFAR-10 dataset.
- Assess the quality of clustering through comparison with ground truth labels.
- Implement the purity score as a performance metric.
- Incorporate the cosine similarity metric for a more interpretable similarity assessment.
