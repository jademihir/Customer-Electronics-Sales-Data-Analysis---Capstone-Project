# 📊 Customer Electronics Sales Data Analysis - Capstone Project

A comprehensive data science project analyzing customer behavior and predicting purchase intent in the electronics market using machine learning algorithms.

## 🎯 Project Overview

This capstone project analyzes customer electronics sales data to understand consumer behavior, product performance, and predict purchasing intent. Through exploratory data analysis and machine learning techniques, the study provides actionable insights for business strategy optimization.

## 📈 Key Results

- **🏆 Best Model Performance**: Random Forest achieved **95.41% accuracy**
- **📊 Dataset Size**: 9,000 customer records analyzed
- **🤖 ML Models**: 4 different algorithms implemented and compared
- **🎯 Primary Objective**: Purchase intent prediction with 95%+ accuracy

## 🗂️ Dataset Features

The dataset contains 9 columns with comprehensive customer and product information:

| Feature | Description |
|---------|-------------|
| `ProductID` | Unique identifier for products |
| `ProductCategory` | Category (Smartphones, Tablets, Laptops, Smart Watches, Headphones) |
| `ProductBrand` | Brand (Samsung, Apple, HP, Sony, Other Brands) |
| `ProductPrice` | Product price range ($100 - $3000) |
| `CustomerAge` | Customer age (18-69 years) |
| `CustomerGender` | Gender (0: Female, 1: Male) |
| `PurchaseFrequency` | Purchase frequency (1-19) |
| `CustomerSatisfaction` | Satisfaction level (1-5 scale) |
| `PurchaseIntent` | Target variable (0: No, 1: Yes) |

## 🔍 Key Findings

### Customer Demographics
- **Gender Distribution**: 51% Male, 49% Female customers
- **Age Range**: Customers aged 18-69 with average age of 43 years
- **Purchase Behavior**: 56.6% of customers show purchase intent

### Product Insights
- **Top Categories**: Laptops (1,842) and Smartphones (1,841) lead sales
- **Leading Brands**: Samsung (1,854) dominates, followed by HP (1,820)
- **Price Distribution**: Uniform distribution across $100-$3,000 range
- **Customer Satisfaction**: Balanced distribution across 1-5 scale

### Business Intelligence
- **Market Leadership**: Samsung holds strongest market position
- **Category Performance**: Laptops and Smartphones drive sales
- **Customer Loyalty**: Moderate satisfaction levels indicate improvement opportunities

## 🤖 Machine Learning Results

| Algorithm | Training Accuracy | Testing Accuracy | Performance |
|-----------|------------------|------------------|-------------|
| **Random Forest** | 100% | **95.41%** | 🥇 Best |
| **Decision Tree** | 100% | 89.52% | 🥈 Second |
| **Logistic Regression** | 81.89% | 81.41% | 🥉 Third |
| **KNN Classifier** | 73.78% | 60.67% | 📉 Lowest |

### Random Forest Performance (Best Model)

## 🛠️ Technology Stack

- **Python 3.x** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Scikit-learn** - Machine learning algorithms
- **Jupyter Notebook** - Development environment

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
Jupyter Notebook
