Food Recommendation System
Overview
This project is a web-based Food Recommendation System that recommends similar food items based on food names, ingredients, and categories. It uses TF-IDF vectorization and cosine similarity to generate relevant recommendations. The system is built using Flask and provides an interactive web interface for users.
Features
Food recommendation based on ingredients and food names
Category-based filtering
TF-IDF and cosine similarity
Fuzzy matching for spelling mistakes
Support for partial and keyword-based searches
Top 5 food recommendations
Interactive and responsive web interface
Handles unknown inputs safely
Tech Stack
Python
Flask
Pandas
Scikit-learn
HTML
CSS
JavaScript
Project Structure
Food_Recommendation_System/
├── backend.py
├── requirements.txt
├── README.md
├── templates/
│   └── index.html
└── static/
    ├── style.css
    └── food_background.png
Installation
Clone this repository.
Install the required packages:
pip install -r requirements.txt
Run the application:
python backend.py
Open the application in your browser:
http://127.0.0.1:5000/
Recommendation Model
Dataset: Food names, ingredients, and categories
Vectorization: TF-IDF
Similarity Measure: Cosine Similarity
Matching: Exact, alias, partial, and fuzzy matching
Output: Top 5 recommended food items
How It Works
The user enters a food name or related keywords.
The input is normalized and checked for exact or common alternative spellings.
TF-IDF converts food names and ingredients into numerical vectors.
Cosine similarity calculates the similarity between food items.
Category filtering is applied if selected.
The most relevant food recommendations are displayed.
Future Improvements
Personalized food recommendations
Nutritional and calorie information
Dietary preference filtering
Larger food dataset
Integration with external food APIs
Online deployment
Author
Developed as an academic Machine Learning project using Python, Flask, and Scikit-learn.
