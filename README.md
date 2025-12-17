# Handwritten_Digit_Recognition

# Project Overview

This project implements a handwritten digit recognition system using multinomial logistic regression on the MNIST dataset.
The objective is to correctly classify grayscale images of handwritten digits (0–9) by learning from pixel intensity values.

The project is implemented in Python using scikit-learn and executed on Google Colab.

# Dataset Description
• Dataset: MNIST Handwritten Digits  
• Total number of samples: 70,000  
• Training samples: 60,000  
• Testing samples: 10,000  
• Image size: 28 × 28 pixels  
• Input features: 784 pixel values per image (flattened)  
• Class labels: Digits from 0 to 9  
( Each pixel value represents the brightness intensity of the corresponding region in the image.)

# Algorithms Used
• Algorithm: Multinomial Logistic Regression  
• Type: Supervised learning, multiclass classification  
• Uses a linear decision boundary  
• Applies Softmax internally to compute class probabilities  
• Optimized using the LBFGS solver  

# Results
• Achieved test accuracy of approximately 93%  
• Most predictions are correctly classified along the diagonal of the confusion matrix  
• Very few misclassifications observed across digit classes  
• Errors mainly occur between visually similar handwritten digits  

# Evaluation Metrics
• Accuracy Score  
• Confusion Matrix (Actual labels vs Predicted labels)

# Tools and Technologies
• Programming language: Python  
• Platform: Google Colab  
• Libraries used:
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-learn

# Conclusion
• Logistic regression successfully classifies handwritten digits with good accuracy  
• The model serves as a strong baseline for image classification tasks  
• Simplicity and interpretability are key advantages of the approach  




