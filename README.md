# Fashion Recommendation System

## Project Overview

The Fashion Recommendation System is a machine learning-based project that generates personalized fashion product recommendations based on product characteristics and similarity.

The system analyzes attributes such as category, color, style, brand, and other product information to identify similar fashion products and recommend relevant items.

## Objectives

* Develop a fashion recommendation system
* Analyze fashion product characteristics
* Generate personalized product recommendations
* Improve product discovery
* Apply machine learning techniques to recommendation systems

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab

## Recommendation Approach

The system uses a **content-based recommendation approach**.

The main steps are:

1. Load the fashion product dataset.
2. Preprocess the product data.
3. Combine relevant product attributes into features.
4. Convert the text features into numerical vectors using **TF-IDF**.
5. Calculate product similarity using **Cosine Similarity**.
6. Generate the top similar fashion products as recommendations.

## Dataset

The project uses a custom CSV dataset containing fashion product information.

The dataset includes attributes such as:

* Product ID
* Product Name
* Category
* Brand
* Color
* Style
* Price
* Rating
* Image File

## Project Structure

```text
Fashion-Recommendation-System-/
│
├── Fashion Recommendation System.ipynb
├── fashion_products(1).csv
├── Mounika_Guttula_Project_Report_Fashion_Recommendation_System.docx
├── README.md
└── requirements.txt
```

## How to Run

### Using Google Colab

1. Open `Fashion Recommendation System.ipynb`.
2. Upload the `fashion_products(1).csv` dataset when prompted.
3. Run the notebook cells in order.
4. Enter or select a product name.
5. The system generates similar fashion product recommendations.

## Example Result

For a sample product such as **UrbanWear Shirt**, the system can recommend similar products based on product feature similarity.

Example recommendations include:

* TrendX Shirt
* Nova Shirt
* EliteFit Shirt
* UrbanWear Hoodie
* StyleHub Shirt

## Project Report

The complete project report is available here:

[Mounika_Guttula_Project_Report_Fashion_Recommendation_System.docx](./Mounika_Guttula_Project_Report_Fashion_Recommendation_System.docx)

## Future Enhancements

* Deep learning-based recommendation
* Image-based fashion recommendation
* Real-time recommendation updates
* User profile integration
* Deployment using Streamlit

## Conclusion

This project demonstrates how machine learning and similarity-based recommendation techniques can be applied to fashion products. By analyzing product features and calculating similarity between products, the system provides relevant fashion recommendations and supports intelligent product discovery.
