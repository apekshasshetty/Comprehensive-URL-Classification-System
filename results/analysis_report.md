# Analysis Report

## 1. Distribution of URLs in Dataset

URL Distribution:

![Dataset](https://github.com/user-attachments/assets/1aa3e6ef-7833-40aa-9414-31b82b569139)

*Figure 1: Bar graph showing the distribution of URLs in the dataset.*

## 2. Classifier Performance Metrics

| Classifier                 | Accuracy (%) | Recall (%) | Precision (%) | F1-Score (%) |
|----------------------------|--------------|------------|---------------|--------------|
| Extra Trees                | 98.81        | 98.81      | 98.78         | 98.74        |
| Random Forest              | 98.53        | 98.53      | 98.49         | 98.44        |
| Decision Tree              | 98.42        | 98.42      | 98.38         | 98.40        |
| K-Nearest Neighbors        | 97.89        | 97.89      | 97.81         | 97.77        |
| Gaussian Naive Bayes       | 90.63        | 90.63      | 92.53         | 90.36        |
| AdaBoost                   | 93.53        | 93.53      | 92.73         | 92.68        |

*Table 1: Classifier performance metrics.*

## 3. Extra Trees Classifier Performance by Class

| Class          | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Benign         | 1.00      | 1.00   | 1.00     | 114429  |
| Defacement     | 0.96      | 0.99   | 0.97     | 28794   |
| Phishing       | 0.89      | 0.62   | 0.73     | 2841    |
| Malware        | 0.96      | 0.75   | 0.84     | 808     |
| **Macro avg**  | **0.95**  | **0.84**| **0.89** | **146872** |
| **Weighted avg** | **0.99** | **0.99** | **0.99** | **146872** |

*Table 2: Extra Trees classifier performance by class.*

## 4. Learning Curve of Extra Trees

![learning curve(ETC)](https://github.com/user-attachments/assets/a9ba0189-3880-4205-9d4b-3b4c9f904763)

*Figure 2: Learning curve of the Extra Trees classifier.*

## 5. Learning Curve of Random Forest

![learning curve(RF)](https://github.com/user-attachments/assets/8a6a15a7-9a58-489a-bbc0-5dc2d2210318)

*Figure 3: Learning curve of the Random Forest classifier.*

## 6. ROC Curve for All Classifiers (Benign vs. Non-Benign)

![BN](https://github.com/user-attachments/assets/33e836d4-a9c1-4039-b48e-6853d3f0c2bf)

*Figure 4: ROC curve for all classifiers (Benign vs. Non-Benign).*

