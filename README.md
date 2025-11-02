# deforestation-cnn-week1
AI-powered deforestation detection using CNN
Submitted by: Bekkari Amulya
Organization: Edunet Foundation
1. Problem Statement
Deforestation is a major environmental issue contributing to climate change,
biodiversity loss, and soil degradation. Manual monitoring of forest changes is
time-consuming and often inaccurate. To ensure sustainability and environmental
protection, there is a need for an automated, AI-based system that can accurately
detect deforestation from satellite images in real time.
2. Objectives
• Develop a Convolutional Neural Network (CNN) model to detect deforestation
from satellite imagery.
• Use Kaggle’s satellite dataset to train and test the model for deforestation
classification.
• Provide visual results showing forested and deforested regions.
• Support sustainable forestry management through AI-driven insights.
3. Literature Review
Recent studies have demonstrated the effectiveness of CNNs in environmental
applications such as crop health monitoring, urban expansion detection, and
deforestation mapping. Kaggle datasets such as 'Planet: Understanding the
Amazon from Space' provide large collections of labeled satellite images suitable
for deep learning models. Combining image classification and spatial analysis
enables the prediction of environmental changes over time.
4. Methodology
The project workflow includes the following steps:
• Collect satellite image data from Kaggle (Planet Amazon Rainforest Dataset).
• Preprocess data by resizing, normalization, and augmentation for CNN training.
Design and train a CNN architecture using TensorFlow/Keras for binary
classification (Deforested vs. Forested).
• Validate the model using accuracy and confusion matrix metrics.
• Visualize predictions and highlight deforestation zones on map images.
5. Dataset Details
Dataset: Planet: Understanding the Amazon from Space (Kaggle) URL: https://ww
w.kaggle.com/competitions/planet-understanding-the-amazon-from-space
Description: The dataset includes labeled satellite images of the Amazon rainforest
depicting various environmental classes, including deforestation, water,
agriculture, and forest regions.
6. Tools & Technologies
• Programming Language: Python
• Libraries: TensorFlow, Keras, NumPy, OpenCV, Matplotlib
• Platform: Kaggle, Google Colab, Jupyter Notebook
• Version Control: GitHub
7. Expected Results
The CNN model is expected to achieve high accuracy in detecting deforested
regions. Visual outputs will mark regions of forest loss in red for easy monitoring.
This solution can aid environmental organizations in sustainable forest
management and early deforestation alerts.
8. Conclusion
This project aims to combine artificial intelligence and sustainability to address a
pressing global issue — deforestation. By leveraging CNN-based deep learning
and satellite data, the project supports the vision of sustainable environmental
monitoring and contributes to the UN Sustainable Development Goals related to
climate action and life on land.
