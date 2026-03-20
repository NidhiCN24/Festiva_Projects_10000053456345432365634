#House_Price_Predictor

Problem statement: To build a ML model to predict house prices, and figure out which attribute contributes the most using MAE and R2 score as the markers.

Dataset description: There are 3 input columns and 1 output column. No missing values are present.
Size_sqft : Area of the house in square feet
Bedrooms : Number of bedrooms
Age : Age of the house (in years)
Price_in_INR : Target variable representing house price in Indian Rupees

Model used : Linear regression

Results: Initially, the MAE score was low and R2 score was high. When age column was removed,the MAE score increased and when Size_per_bedroom column was added, MAE score decreased a lot. This shows that it is a very important feature for the dataset.

Conclusion: Linear Regression successfully models the relationship between house features and price, and despite a small dataset, the model achieved strong predictive performance. 



#Fake_News_Detector

Problem Statement: With the rapid spread of information online, distinguishing between real and fake news has become increasingly difficult. Fake news can mislead people, create panic, and influence public opinion. The goal of this project is to build a machine learning model that can automatically classify news articles as Real or Fake using Natural Language Processing techniques.

Approach:The project begins with exploring the WELFake dataset to understand its structure and label distribution, followed by basic preprocessing such as removing missing values and filtering noisy text. The cleaned data is then split into training and validation sets while maintaining class balance. Text data is tokenized using a pretrained DistilBERT tokenizer with appropriate padding and truncation to ensure consistent input size. The processed data is converted into a format suitable for model training, and a pretrained DistilBERT model is fine-tuned on this dataset. Finally, the model’s performance is evaluated using standard metrics.

Model Used: DistilBERT (distilbert-base-uncased)

Metrics: Accuracy,Precision,Recall,F1-score,Confusion Matrix 

Improvements: Handled class imbalance using weighted loss, increased input sequence length to capture more context, and balanced the dataset to avoid model bias toward one class

Key Learnings: Pretrained models like BERT are powerful but require careful preprocessing, proper label handling, and balanced data to perform well.
Even small adjustments like improving input length or handling class imbalance can significantly impact model performance.




