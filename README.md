# Plant Leaf Disease Classification

This project focuses on the classification of plant leaf diseases using the EfficientNet B3 deep learning architecture.
## Abstract

Plants can be affected by various diseases.  Identifying and properly managing foliar plant diseases is important to ensure crop health and agricultural productivity. Conventional manual screening methods require extensive pathogen knowledge, and are labour-intensive and inefficient for large-scale agriculture. This work addresses these problems by developing YR2S (YOLO-Enhanced Rat Swarm Optimizer - Red Fox Optimization (RFO-ShuffleNetv2)), an efficient framework designed for accurate and efficient detection of plant leaf diseases. The framework incorporates state-of-the-art techniques including pre-processing using contrast-limited adaptive histogram equalization (CLAHE), feature extraction using Pyramid Channel-based Feature Attention Network (PCFAN), anomaly detection using YOLOv7, and classification optimization using Enhanced Rat Swarm Optimizer (RSO) and ShuffleNetV2 [1].  In addition, the Red Fox optimization algorithm is used for disease classification. The proposed framework is evaluated on the ‘Plant Village Dataset’. This solves problems such as high parameters, slow detection and difficulty in identifying small and dense areas. This work contributes to precision agriculture by providing a robust and efficient solution for the automatic detection of plant leaf diseases, thereby promoting early intervention against diseases and reducing agricultural losses. There are several accurate and highly efficient techniques in the literature, but these need to be tested and deployed in real-time mobile applications and web services. So, a web-based tool is developed that allows the users to interact directly with the model. Therefore, farmers can also utilize these unconventional automatic plant disease detection models openly by taking photos of suspicious plant leaves.

## Dataset

We used the PlantVillage dataset, which contains 38 classes and 70,295 images of 14 different plant species. The dataset includes both healthy and diseased leaf images. Augmentation techniques were applied during training to obtain diverse images for each disease category.

The classifier can classify the following 33 classes:
- Apple (Apple Scab, Black Rot, Cedar Apple Rust, Healthy)
- Cherry (Powdery Mildew, Healthy)
- Corn (Gray Leaf Spot, Common Rust, Northern Leaf Blight, Healthy)
- Grape (Black Rot, Esca, Leaf Blight, Healthy)
- Peach (Bacterial Spot, Healthy)
- Pepper Bell
-and so on
