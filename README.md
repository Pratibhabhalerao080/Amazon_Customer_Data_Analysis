# Amazon Customer Data Analysis

This repository contains a Python script for analyzing Amazon customer data using the Pandas, NumPy, Matplotlib, Seaborn, and TextBlob libraries. The analysis includes data preparation, user behavior, product reviews, and sentiment analysis.

## Dependencies

Before running the script, make sure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- sqlite3
- warnings
- textblob

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn textblob
```

## Usage

1. Clone this repository to your local machine or download the script.

2. Make sure you have the Amazon customer data in an SQLite database. You can modify the `con` variable to specify the path to your database:

```python
con = sqlite3.connect('your_database_path')
```

3. Open and run the Python script. It will perform the following analyses:

   a. Data Preparation: Removes invalid rows and duplicates from the dataset.

   b. Analyze User Behavior: Investigates user behavior by counting the number of summaries, texts, average scores, and products purchased for each user.

   c. Which Product Has Good Reviews: Identifies products with a high number of reviews.

   d. Differences Between Frequent and Not Frequent Viewers: Analyzes user behavior and score distribution for frequent and not frequent viewers.

   e. Are Frequent Users More Verbose: Compares the text length of reviews for frequent and not frequent viewers.

   f. Sentiment Analysis: Performs sentiment analysis on the review summaries and identifies the most common positive and negative summaries.

## Results

The script provides insights into Amazon customer data, including user behavior, popular products, differences between frequent and not frequent viewers, and sentiment analysis of review summaries.

You can use these results to make data-driven decisions or conduct further analysis.

## License

This project is licensed under the MIT License. Feel free to modify and use the script for your own analysis.

If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Happy analyzing!
