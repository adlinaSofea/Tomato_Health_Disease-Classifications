# Tomato_Health_Diseases-Classifications With Convolutional Neural Networks (CNN)

<h3>Description</h3>
<p>This repository contains a comprehensive analysis of Tomato Health Diseases classification using various convolutional neural network (CNN) models. It is part of the project for the Principles of Artificial Intelligence subject, focusing on model performance evaluation and improvement strategies.Detailed analysis of confusion matrices, training accuracy, and loss trends are included to provide comprehensive insights.</p>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h3>Overview</h3>
<p>Tomato health disease classification is a challenging task due to the subtle visual differences between various diseases. This project employs three popular neural network architectures—ResNet50, DenseNet121, and MobileNetV3Small—to address this classification problem. The goal is to analyze their performance, identify areas for improvement, and suggest enhancements for better disease detection and classification in tomato leaves.</p>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h3>Content</h3>
<ul>
<li>This project contains 13,899 images, retrieved from the Kaggle website. The dataset includes 8 classes of tomato leaf conditions used for training the model. It is split into three categories: Training, Validation, and Testing.</li>

<li>The images are split using a ratio of 70% for Training, 15% for Validation, and 15% for Testing.</li>

<li>The dataset is not equally distributed among the classes. For example, Tomato_Yellow_Leaf_Curly_Virus has over 3,209 images, while the other classes have around 1,000 to 2,000 images. This imbalance may cause the model to achieve high accuracy during initial training, which can be misleading.</li>

<li>Training Model and Loss</li>
    <p>- Examines the evolution of training and validation accuracy. Analyzes training and validation loss to understand overfitting or underfitting trends.</p>

<li>Confusion Matrix Analysis:</li>
   <p>- Provides a visual summary of the the three models. Highlights key metrics, such as correct classifications and misclassifications. Offers detailed insights into error patterns and potential biases in the model.</p>

 <li>Model Evaluation Comparison:</li>
   <p> To compare the performance of the three CNN models—**ResNet50**, **DenseNet121**, and **MobileNetV3Small**—We evaluated them using accuracy, training time, and confusion matrices. Each model was trained for **50 epochs** with the same dataset split and preprocessing pipeline.
ResNet50 achieved an accuracy of 98.33% and loss of 5.390% with a training time of 4507.30 seconds.

DenseNet121 showed slightly better performance with 97.32% accuracy along with 8.09& of loss and a training time of 2001.54 seconds.

MobileNetV3Small, being a lightweight model, trained faster (1698.36 seconds) but had a slightly lower accuracy than DenseNet121 but still in a better performance of 96.89% and loss of 9.06% compared to the others.

The confusion matrix revealed that all three models performed best on the dominant class (Tomato_Yellow_Leaf_Curly_Virus) but showed varying precision and recall for minority classes.</p>

  <li>mAP (Mean Average Precisions) Analysis:</li>
    <p>The **mean average precision (mAP)** provides a more balanced metric than accuracy, especially for imbalanced datasets. It considers both **precision** and **recall** across all classes.
ResNet50 achieved a mAP of 99.60%, indicating strong overall precision and recall across classes.

DenseNet121 achieved a mAP of 99.44%, showing its ability to generalize well across categories.

MobileNetV3Small achieved a mAP of 99.11, which, while slightly lower, is still effective given its efficiency and lower parameter count.

This metric highlights that ResNet50 provides the best balance between performance and generalization, making it the most suitable model for tomato disease classification in this project.</p>
</ul>

<h3>Project by:</h3>
<ul>
  <li>NUR ADLINA SOFEA BINTI MAHDZIR</li>
  <li>NOR NAJLAH HANINI BINTI HAIRUL NIZAM</li>
  <li>MUHAMAD IZZAT A'KIF BIN MOHD SANUSI</li>
</ul>

