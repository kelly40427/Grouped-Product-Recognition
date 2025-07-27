# Grouped Product Recognition from Images of Supermarket Shelves using Machine Learning
We proposed an unsupervised framework for grouped product recognition, designed to detect and cluster visually similar or identical products directly from shelf images in supermarket environments without requiring human-labeled data. Although object detection and recognition of retail products are still in their infancy, this task introduces additional challenges such as highly similar packaging. This unsupervised three-stage framework integrates YOLOv5 product detection, product characterization that combines visual, textual, and spatial information, and clustering methods using Agglomerative Clustering and OPTICS.

We evaluated this framework on two public datasets (Grocery Products, WebMarket) and a newly collected real-world dataset, Dutch Markets. Results show that integrating CNN, color, and spatial features achieved the highest performance.

## Summary of the Method
