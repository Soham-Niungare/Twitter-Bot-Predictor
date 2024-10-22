# Twitter Bot Predictor

## Project Overview
The **Twitter Bot Predictor** is a machine learning project designed to classify Twitter accounts as either bots or humans based on their activity, content, and engagement metrics. The project leverages various machine learning algorithms and techniques to analyze Twitter data and predict whether an account is a bot.

## Features
- **Data Collection**: Automatically gather Twitter data using the Twitter API.
- **Data Preprocessing**: Clean and preprocess data for analysis.
- **Model Training**: Train various machine learning models (e.g., Random Forest, Logistic Regression) to predict bot accounts.
- **Model Evaluation**: Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Visualization**: Visualize data and model performance with graphs and charts.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Twitter API (tweepy)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Soham-Niungare/Twitter-Bot-Predictor.git
2. Navigate to the project directory:
   ```bash
   cd Twitter-Bot-Predictor
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   
##Usage
1. Set up your Twitter API credentials in the config.py file.
2. Run the data collection script:
   ```bash
   python data_collection.py
3. Train the model:
   ```bash
   python train_model.py
4. Evaluate the model:
   ```bash
   python evaluate_model.py
