# Sephora Personalized Recommendation System 🌟

Welcome to the Sephora Personalized Recommendation System repository! 💄👠🛍️

![Sephora-Logo](https://github.com/RoshankumarS14/Personalized-Recommendation-System-for-Ecommerce-Sephora-/assets/123869873/6ea33312-6c9d-4d02-a714-4ba0ff7ba0dd)
<img src="https://github.com/RoshankumarS14/Personalized-Recommendation-System-for-Ecommerce-Sephora-/assets/123869873/6ea33312-6c9d-4d02-a714-4ba0ff7ba0dd" alt="Sephora Logo" width="200">

## 📜 Table of Contents

- [🚀 Introduction](#introduction)
- [📊 Data](#data)
- [🧹 Preprocessing](#preprocessing)
- [🛠️ Feature Engineering](#feature-engineering)
- [🌟 Similarity Analysis](#similarity-analysis)
- [🤝 User Clustering](#user-clustering)
- [📢 Sentiment Analysis](#sentiment-analysis)
- [🎁 Recommendation Engine](#recommendation-engine)
- [🔍 Filtering](#filtering)
- [🖥️ User Interface](#user-interface)
- [🚀 Deployment](#deployment)
- [📋 Usage](#usage)
- [🤝 Contributing](#contributing)
- [📄 License](#license)

## 🚀 Introduction

The Sephora Personalized Recommendation System is an innovative project aimed at providing tailored product recommendations to Sephora customers. Leveraging the power of data science and machine learning, we've created a system that understands your preferences, considers product similarities, and groups users to offer a unique shopping experience. 🛒✨

## 📊 Data

Our system utilizes two main datasets:

- **Review Dataset**: Contains customer reviews and ratings for Sephora products.
- **Product Dataset**: Contains information about Sephora's product catalog. 📦📊

## 🧹 Preprocessing

We took great care in preparing our data for analysis. Our preprocessing steps include:

- Merging and cleaning the datasets.
- Target encoding and label encoding for categorical features.
- Imputing missing values using a Decision Tree-based approach.
- Converting encoded columns back to their original states. 🧹🔍

## 🛠️ Feature Engineering

To enhance the recommendation system's performance, we engineered features by:

- Creating a product-product similarity matrix:
  1. Comparing ingredients using CHEMBERT.
  2. Analyzing product names using TF-IDF.
  3. Evaluating highlights with BERT embeddings. 💡🔍

## 🌟 Similarity Analysis

We understand that product similarity is crucial for personalized recommendations. Our system computes similarity scores based on various product attributes, ensuring that you receive recommendations that align with your preferences. 🤝📊

## 🤝 User Clustering

Not all customers are the same, and we acknowledge that. We've grouped users into different clusters based on their attributes, allowing us to provide recommendations that are more aligned with their individual tastes. 🧑‍🤝‍🧑🔍

## 📢 Sentiment Analysis

We care about the quality of your shopping experience. To ensure that our recommendations are based on authentic feedback, we've performed sentiment analysis on review titles and text. 📝🙂

## 🎁 Recommendation Engine

Our recommendation engine combines all the data and analysis to provide you with the most relevant product recommendations. Whether you're a makeup enthusiast or skincare aficionado, our system has something special for you. 🎁✨

## 🔍 Filtering

We understand that you may have specific interests. Our system allows you to filter recommendations based on product categories, so you can find exactly what you're looking for. 🧐🔍

## 🖥️ User Interface

We've created a user-friendly interface using tkinter for desktop applications and Streamlit for web deployment, ensuring that you can easily access and enjoy our recommendations. 💻🌐

## 🚀 Deployment

Our system is deployed and ready to serve you. Whether you prefer the desktop or web experience, we've got you covered. 🚀🌐

## 📋 Usage

- Clone the repository.
- Install the required dependencies.
- Run the application for personalized Sephora recommendations. 🚀👩‍💻

## 🤝 Contributing

We welcome contributions from the community. Whether it's improving the recommendation algorithm, adding new features, or enhancing the user interface, your input is valued. 🤗🤝

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 📜📄

---

Thank you for choosing Sephora's Personalized Recommendation System. We're excited to provide you with a personalized shopping experience that will keep you coming back for more. Happy shopping! 🛒💄🎉
