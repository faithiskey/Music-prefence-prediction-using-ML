### Project description
This Project predicts user music preference based on their listening habits using Machine Learing techniques. it explores supervised learning algorithms to analyze patterns and classify music genres effectively.

### Dataset
This dataset contains information about a sample of individuals and their music preferences, including age, gender and genre.
data source: kaggle

### Tools
The language used is python, the tool used is Goodle colab

### Exploratory Data Analysis
- Getting a sence of the data types(numerical, categorical).
- Checking the size of the dataset(no of rows and columns).
- Understanding the meaning and relevance of each feature (column).

### Features
- Age: Represents the age of the individual. This is numerical variable.
- Gender: A binary categorical variable, where:
- 1 = Male
- 0 = Female
- Genre: A categorical variable that represents the genre of music preferred by the individual\.
  The possible values are:
- Hip-Hop
- Jazz
- Classsical
- Dance
- Acoustic

### Model Building
1. Data Splitting: The dataset was split into 80% training and 20% testing using train_test_split.

2. Model Training: A model was selected and trained using the training data (feature_train, target_train).

3. Prediction: Predictions were made on the test set (feature_test).

4. Evaluation: Model performance was evaluated using relevant metrics (e.g., accuracy).

### Model Performance
1. Evaluation Metric: The model's performance was evaluated using accuracy.

2. Results: The model achieved an accuracy score of 0.75, meaning it correctly predicted 75% of the test data.
