## FASHION-MNIST
### Abstract
This project presents a comparative study of traditional machine learning models and a deep learning approach for a supervised classification task. Support Vector Machine (SVM), Random Forest, and a Convolutional Neural Network (CNN) are implemented and evaluated. An ensemble learning technique based on average probability voting is proposed to enhance classification performance. Experimental results show that the ensemble model achieves improved accuracy and generalization compared to individual models.

### Index Terms
Machine Learning, Deep Learning, Classification, Ensemble Learning, Convolutional Neural Network

#### Introduction
Supervised classification is a fundamental problem in machine learning with applications across multiple domains. Traditional machine learning models depend on handcrafted feature representations, while deep learning models automatically learn hierarchical features. This project compares these approaches and evaluates the effectiveness of ensemble learning in improving predictive performance.

#### Dataset Description
The dataset consists of labeled numerical features suitable for supervised classification. Data preprocessing included reshaping features for compatibility with both traditional machine learning models and convolutional neural networks. The dataset was split into training and testing subsets to ensure unbiased evaluation.

#### Methodology
The Support Vector Machine model was trained with probability estimation enabled to facilitate ensemble integration. Random Forest was used as a tree-based ensemble learner to capture non-linear relationships. A Convolutional Neural Network was implemented using TensorFlow/Keras to automatically extract feature representations. The ensemble model combines probability outputs from all three models using average voting, and the final class label is selected using the maximum probability.

#### Results and Discussion
All individual models demonstrated competitive performance. The ensemble model consistently achieved higher accuracy and improved generalization by leveraging the strengths of heterogeneous classifiers.

#### Conclusion
This project demonstrates that ensemble learning improves classification performance by combining traditional machine learning and deep learning models. The proposed ensemble approach provides a robust and effective solution for supervised classification tasks.

