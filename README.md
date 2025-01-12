# A Methodology to Rank Importance of Frequencies and Channels in Electromyography Data with Decision Tree Classifiers

This repository contains the implementation of the methodology presented in the paper *"A Methodology to Rank Importance of Frequencies and Channels in Electromyography Data with Decision Tree Classifiers"* by A.A. Nasybullin, N.Abdullaev, M.A.Baranov, V.V.Koshman, and V.A.Mahonin. The study proposes a method for identifying the most informative frequencies and channels in electromyography (EMG) data using Decision Tree classifiers, with a focus on muscle recovery evaluation.

## Summary

In this study, EMG signals recorded from the vastus lateralis muscle during squat exercises were analyzed across varying rest intervals to assess optimal recovery periods. Single Decision Tree classifiers were employed to enhance interpretability and provide insights into feature importance. This method is critical for applications in medical and sports fields, where transparency in models is essential.

The experimental protocol includes:
- **Grid search for hyperparameter tuning**
- **Cross-validation to address class imbalance**
- **Classification of rest intervals based on power spectral density features**

The results highlight that a limited subset of highly informative features can provide sufficient classification accuracy, suggesting the effectiveness of interpretable, streamlined models in muscle recovery evaluation.

## Key Features
- **EMG Signal Classification**: Classifies rest intervals based on EMG data.
- **Decision Tree Classifier**: A single decision tree approach used to ensure model interpretability.
- **Feature Importance Ranking**: Identifies key frequencies and channels contributing to classification accuracy.
- **Hyperparameter Tuning**: Uses grid search for hyperparameter optimization.
- **Cross-Validation**: Applies cross-validation to manage class imbalance and improve model reliability.

## Repository structure

├── data/                      # Folder containing the EMG data files. Direcotry name stands for patient ids


Nasybullin, A.A., Abdullaev, N., Baranov, M.A., Koshman, V.V., & Mahonin, V.A. (Year). A Methodology to Rank Importance of Frequencies and Channels in Electromyography Data with Decision Tree Classifiers. Journal/Conference Name. DOI: 10.20537/nd241216.

https://www.researchgate.net/publication/387495516_A_Methodology_to_Rank_Importance_of_Frequencies_and_Channels_in_Electromyography_Data_with_Decision_Tree_Classifiers
