# Grouped Product Recognition from Images of Supermarket Shelves using Machine Learning
We proposed an unsupervised framework for grouped product recognition, designed to detect and cluster visually similar or identical products directly from shelf images in supermarket environments without requiring human-labeled data. Although object detection and recognition of retail products are still in their infancy, this task introduces additional challenges such as highly similar packaging. This unsupervised three-stage framework integrates YOLOv5 product detection, product characterization that extracts visual, textual, and spatial information, and unsupervised clustering methods using Agglomerative Clustering and OPTICS.

We evaluated this framework on two public datasets (Grocery Products, WebMarket) and a newly collected real-world dataset, Dutch Markets. Results show that integrating CNN, color, and spatial features achieved the highest performance.

## Summary of the Method
The proposed framework operates in three stages. First, YOLOv5 is used to detect and localize individual grocery items within the input image. Second, each cropped product goes through feature characterization, where multiple types of features are extracted, including CNN-based deep features, color histograms, shape and texture information, text from packaging, and spatial information. Finally, these features are fused into a single vector and passed to the grouped product recognition stage, which applies two unsupervised clustering algorithms: Agglomerative Clustering and OPTICS. This stage clusters visually similar products into groups without requiring manual labels.

![Grouped product recognition framwork](paper/project_process.drawio.png)

## Validation
**Datasets:**

**Evaluation metrics:**

**Results:**
