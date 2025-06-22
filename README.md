# EatWise: Restaurant Recommendation & Food Data Analysis

**EatWise** is a data-driven project focused on analyzing restaurant data from popular food delivery platforms (Swiggy and Zomato) to help users make informed dining choices. The project leverages machine learning and data analytics to provide insights into restaurant ratings, prices, cuisine types, delivery times, and more.

---

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset Details](#dataset-details)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Project Overview

EatWise aims to analyze and compare restaurant data from Swiggy and Zomato, providing users with a comprehensive view of food options, ratings, prices, and delivery times. The project can be extended to include personalized recommendations, food type preferences, and even sustainability metrics. The core goal is to empower users to make healthier, more informed, and efficient food choices.

---

## ✨ Features

- **Data Integration:** Combines restaurant data from Swiggy and Zomato for comprehensive analysis.
- **Rating & Price Analysis:** Visualizes and analyzes restaurant ratings, prices, and delivery times.
- **Cuisine Filtering:** Filters restaurants by cuisine type for tailored recommendations.
- **Machine Learning:** Uses Random Forest Regressor to predict restaurant scores based on features like rating, price, and delivery time.
- **Target Score Calculation:** Computes a custom target score for each restaurant to aid in recommendation.
- **Easy-to-Use Notebook:** Jupyter notebook for interactive data exploration and model training.

---

## 📊 Dataset Details

The project uses the following datasets:

- **swiggy.csv** – Contains restaurant details such as ID, Area, City, Restaurant Name, Price, Avg Ratings, Total Ratings, Food Type, Address, and Delivery Time.
- **zomato_dataset.csv** – Contains data like Restaurant Name, Rating, Cuisine, Average Price, Average Delivery Time, Safety Measure, and Location.

Sample data structure for both datasets is available in the notebook.

---

## 🚀 Getting Started

To get started with EatWise, clone this repository and install the required dependencies.

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/eatwise.git
cd eatwise
```

Install Python dependencies:

```bash
pip install pandas numpy scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `EatWise.ipynb` to interact with the project.

---

## 🧪 Usage

Load your datasets:

```python
df = pd.read_csv("swiggy.csv")
df1 = pd.read_csv("zomato_dataset.csv")
```

Explore and analyze the data:  
Use the provided notebook to visualize ratings, prices, delivery times, and cuisine types.

Train the recommendation model:  
The notebook includes code for training a Random Forest Regressor to predict restaurant scores.

Generate recommendations:  
Based on the target score, users can filter and select the best restaurants for their preferences.

---

## 🛠 Technologies Used

- **Python:** Core programming language
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical operations
- **scikit-learn:** Machine learning model training and evaluation
- **Jupyter Notebook:** Interactive data exploration and visualization

---

## 📌 Examples

Here’s a sample of the data structure after integration:

| Restaurant Name | Rating | Cuisine | Average Price | Average Delivery Time | Location  | Platform | Target Score |
|------------------|--------|---------|----------------|------------------------|-----------|----------|---------------|
| Tandoor Hut      | 4.4    | Biryani,Chinese,North Indian,South Indian | 150.0 | 59 | Bangalore | Swiggy   | 3.070 |
| Tunday Kababi    | 4.1    | Mughlai,Lucknowi                          | 150.0 | 56 | Bangalore | Swiggy   | 2.830 |
| Kim Lee          | 4.4    | Chinese                                  | 325.0 | 50 | Bangalore | Swiggy   | 3.075 |

---

## 🤝 Contributing

We welcome contributions! Please fork the repository and submit a pull request with your improvements.

---

## 📃 License

This project is licensed under the **MIT License**.

---

Enjoy exploring and recommending the best food options with **EatWise**! 🎉
