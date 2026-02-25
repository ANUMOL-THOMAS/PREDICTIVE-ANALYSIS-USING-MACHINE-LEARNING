# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
*Company*: CODTECH IT SOLUTIONS PRIVATE LIMITED
*Name*:ANUMOL THOMAS
*Intern ID*:CTIS3469
*Domain*: DATA ANALYSIS
*Duration*: 6 WEEKS
*Mentor*: NEELA SANTHOSH KUMAR

## MACHINE LEARNING PREDICTIVE ANALYSIS - WINE QUALITY DATASET

This project explores the fascinating intersection of viticulture and data science, using a predictive analysis workflow to determine the sensory quality of red wine. Traditionally, assessing wine is the job of a sommelier—a process that is inherently subjective, time-consuming, and difficult to scale. By leveraging machine learning, specifically the Support Vector Machine (SVM) algorithm, I’ve demonstrated how 11 distinct chemical properties, like pH levels and alcohol content, can be modeled to classify wine quality with high objective accuracy. This provides a reproducible framework for wineries to predict how a bottle will rank before it ever hits a tasting room.

Using the UCI Red Wine Quality dataset, which features nearly 1,600 samples of Portuguese "Vinho Verde," the analysis digs into the chemical markers that define a great vintage. During the feature selection phase, a correlation heatmap revealed that alcohol and sulfates are the strongest positive drivers of quality. Conversely, volatile acidity-the culprit behind that unpleasant, vinegar-like aroma—serves as the primary red flag. A critical step in this process was implementing a "StandardScaler." Because chemicals are measured in vastly different units ,some in large milligrams and others in tiny decimals standardization ensures the model treats every feature fairly, preventing it from being biased by the sheer size of the numbers.

For the predictive engine, I chose an SVM with a Radial Basis Function (RBF) kernel. This model is particularly effective here because it excels at finding the "sweet spot" between different quality categories in complex, high-dimensional data. By splitting the data into a training and testing set, I ensured the model was actually learning to recognize quality rather than just memorizing the specific samples. The final evaluation, backed by a classification report and confusion matrix, confirms that raw chemical data can indeed reliably predict how a wine will taste.

The model showed impressive precision in identifying "average" and "good" wines. However, it did face the common real-world hurdle of "imbalanced data," where the rarity of truly elite, high quality samples in the dataset made them harder to predict perfectly. Ultimately, this analysis proves that machine learning can successfully decode the complex relationship between chemistry and flavor, offering a scalable, data-driven alternative to traditional tasting panels. Future versions could sharpen this even further by using advanced sampling techniques to better represent those rare, top-tier vintages.

# OUTPUT

<img width="940" height="248" alt="Image" src="https://github.com/user-attachments/assets/5b537ba8-7624-486f-b2e8-45add66b5283" />

<img width="940" height="341" alt="Image" src="https://github.com/user-attachments/assets/9065e980-4fb2-48ee-b064-ec491eebfcbb" />

<img width="940" height="283" alt="Image" src="https://github.com/user-attachments/assets/04431d1c-9d6c-4bb7-b0da-9c3b5bc74a33" />

<img width="940" height="196" alt="Image" src="https://github.com/user-attachments/assets/181c4494-bf90-49c8-ae7c-703b5f302d79" />

<img width="940" height="345" alt="Image" src="https://github.com/user-attachments/assets/6fcc842a-42d0-4f86-9346-2d596c8d446e" />
