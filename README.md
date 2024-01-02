## Juice Shop Reviews Analysis

# Overview
The Juice Shop Reviews Analysis project aims to analyze customer reviews from juice shops in Tier 1 and Tier 2 cities in India using the Google Places API and Python data analysis libraries. The analysis focuses on extracting insights from customer feedback to identify areas of improvement and enhance customer satisfaction.

# Features
Data Retrieval: Fetch juice shop reviews using the Google Places API.
Aspect-Based Sentiment Analysis: Analyze sentiments within specific categories such as taste, service, price, cleanliness, and ambience.
Feedback Categorization: Categorize customer feedback based on predefined aspects to prioritize areas for improvement.
Visualization: Visualize sentiment analysis results using bar charts to represent negative feedback volume and sentiment polarity within each category.

# Prerequisites
Python 3.x
Google Cloud Platform Account with API Key for Google Places API
Required Python Libraries: pandas, matplotlib, seaborn, textblob, googlemaps

Setup Instructions
Clone the repository:

git clone https://github.com/yourusername/juice-shop-reviews-analysis.git
Navigate to the project directory:

cd juice-shop-reviews-analysis
Install the required Python libraries:

pip install -r requirements.txt
Obtain Google Places API Key and set up Google Cloud project:

Create a Google Cloud project and enable the Google Places API.
Generate an API key and replace 'YOUR_API_KEY' in the code with your actual API key.
Run the Python scripts to perform data analysis:

python data_retrieval.py
python sentiment_analysis.py
python feedback_categorization.py

# Usage
Ensure that you have set up the Google Cloud project and obtained the API key.
Follow the setup instructions to install the required dependencies and run the Python scripts.
Analyze the generated insights and visualizations to identify areas for improvement based on customer feedback.
