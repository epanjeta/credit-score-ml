# Credit Score Machine Learning Project

### The primary goal of this project is to develop a credit score prediction model using the KNN algorithm.

The provided dataset contained some bad data, which had to be cleaned up and transformed before it could be used for training the model. This involved removing invalid values, correcting errors, and filling in missing data using appropriate techniques. Additionally, some columns had to be converted from text to numerical format, while others had to be split into multiple columns to extract useful information.

After the data was preprocessed and transformed, the team used the Pandas library to analyze the dataset and identify the most important features that affect the credit score. This helped to determine which variables to include in the model and which to exclude.

Finally, the team used the KNN algorithm to train the credit score prediction model. The model takes into account a range of factors, to provide an accurate prediction of an individual's credit score.

After preprocessing and transforming the data, several KNN models were built. Models were created without scaled data, with scaled data using min-max, with scaled data using z transformation, and with undersampling and oversampling. Models were also created with tuned parameters of the KNN algorithm. Cross-validation was conducted to evaluate the performance of the models before and after tuning.

The performance of each model was evaluated using appropriate metrics, and the best-performing model was selected. Before any parameter tuning, the accuracy of the model was around 70%. However, after parameter tuning, the accuracy increased to around 81%, which is a significant improvement.

Here are the confusion matrices before and after parameter tuning:

* Before tuning:

![conf1](https://user-images.githubusercontent.com/73060315/236341719-14877f4f-c53b-4ff3-b81a-e9024182cf46.png)

* After tuning:

![conf2](https://user-images.githubusercontent.com/73060315/236341841-8b275386-a296-4deb-b213-d0ba3c5d2514.png)
