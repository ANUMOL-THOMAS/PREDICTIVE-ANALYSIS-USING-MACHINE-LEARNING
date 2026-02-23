# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
*Company*: CODTECH IT SOLUTIONS PRIVATE LIMITED
*Name*:ANUMOL THOMAS
*Intern ID*:CTIS3469
*Domain*: DATA ANALYSIS
*Duration*: 6 WEEKS
*Mentor*: NEELA SANTHOSH KUMAR

## MACHINE LEARNING PREDICTIVE ANALYSIS - WINE QUALITY DATASET

This project explores the intersection of viticulture and data science through a Predictive Analysis workflow designed to determine the sensory quality of red wine. Traditionally, wine quality is assessed by human sommelier panels, a process that is inherently subjective, time-consuming, and difficult to scale. By utilizing machine learning, specifically the Support Vector Machine (SVM) algorithm, we demonstrate how 11 distinct physicochemical properties—such as pH levels, sulphates, and alcohol content—can be modeled to classify wine quality scores with high objective accuracy. This approach provides a reproducible framework for wineries to predict product quality before it ever reaches a tasting room. The analysis utilizes the UCI Red Wine Quality dataset, which contains 1,599 samples of Portuguese "Vinho Verde" wine. Each sample is defined by chemical markers including fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol percentage.

During the feature selection phase, we employed a correlation heatmap to visualize the linear relationships between these chemicals and the target quality score. This step revealed that Alcohol and Sulphates are the most significant positive drivers of quality, whereas Volatile Acidity—often responsible for an unpleasant vinegar-like aroma—serves as the primary negative indicator. A critical component of this workflow was the implementation of the `StandardScaler`. In chemical datasets, features are measured in vastly different units; for instance, sulfur dioxide is measured in milligrams per decimeter, while chlorides are measured in much smaller decimals. Without scaling, the SVM model would erroneously prioritize features with larger numerical magnitudes. Standardization transforms the data such that each feature has a mean of zero and a standard deviation of one, ensuring that the model’s logic is not biased by the scale of the measurements.

For the predictive engine, we selected a Support Vector Machine (SVM) with a Radial Basis Function (RBF) kernel. SVM is particularly well-suited for this dataset because it excels in high-dimensional spaces where the boundaries between classes are non-linear. The model works by identifying an optimal hyperplane that maximizes the margin between different quality categories. By splitting the data into an 80% training set and a 20% testing set, we ensured the model could generalize its learning to unseen chemical profiles rather than simply memorizing the training data. The final evaluation using a classification report and a multi-class confusion matrix confirms that objective chemical data can reliably predict sensory quality.

The model showed exceptional precision in identifying "average" and "good" wines, though it faced challenges with "rare" high-quality wines due to the limited number of such samples in the dataset—a common hurdle in real-world imbalanced data. In conclusion, this analysis proves that machine learning can successfully decode the complex relationship between chemical composition and taste, providing a scalable, data-driven alternative to traditional tasting panels. Future iterations could improve accuracy further by employing oversampling techniques like SMOTE to better represent the highest-quality vintages.

# OUTPUT

<img width="940" height="248" alt="Image" src="https://github.com/user-attachments/assets/5b537ba8-7624-486f-b2e8-45add66b5283" />

<img width="940" height="341" alt="Image" src="https://github.com/user-attachments/assets/9065e980-4fb2-48ee-b064-ec491eebfcbb" />

<img width="940" height="283" alt="Image" src="https://github.com/user-attachments/assets/04431d1c-9d6c-4bb7-b0da-9c3b5bc74a33" />

<img width="940" height="196" alt="Image" src="https://github.com/user-attachments/assets/181c4494-bf90-49c8-ae7c-703b5f302d79" />

<img width="940" height="345" alt="Image" src="https://github.com/user-attachments/assets/6fcc842a-42d0-4f86-9346-2d596c8d446e" />
