# Alex's Portfolio

## Welcome!

Hi, welcome to my portfolio site! I'm Alex Zheng, an economics student with a passion for data science and machine learning. Here you can find information about my projects.

---

## [Project 1: Hong Kong Housing Price Data Science Project](https://github.com/alexzheng123/Hong-Kong-Housing-Price)

- Scraped housing information from Centaline Property Agency.
- Cleaned and processed the data, including geocoding addresses.
- Conducted various visualisations and analyses to understand the housing market in Hong Kong.
- Investigated the influence of location and house size on property prices.

**Key insights:**
- Location has a more significant impact on house prices than size.
- Detailed visualisations of housing data on an interactive map.
- Statistical analysis revealing correlations between price and area.

**Key Highlights:**

![Geographical Distribution of Housing Prices](images/project1/map_figure.png)
![Price per Square Foot vs Area](images/project1/price_per_sq_foot_vs_area_scatter.png)

---

## [Project 2: Buenos Aires Housing Price Prediction Project](https://github.com/alexzheng123/Buenos-Aires-Property-Market)

- Focused on predicting housing prices in Buenos Aires based on factors such as size, location, and neighbourhood.
- Divided analysis into several notebooks, each addressing different aspects of the prediction model.

### Notebooks Overview

#### 1. Prepare Data

- Prepared the dataset by cleaning, handling missing values, and conducting initial exploratory data analysis.

**Key steps:**
- Plotted a histogram of `surface_covered_in_m2` and removed outliers.
- Built a data wrangling function to filter data for houses.

#### 2. Predicting House Price with Size

- Explored the relationship between house size and price using a linear regression model.

**Key steps:**
- Plotted the distribution of house sizes and a scatter plot of price vs. area.
- Calculated the correlation between `surface_covered_in_m2` and `price_aprox_usd`.
- Built and evaluated a baseline and linear regression model.

#### 3. Predicting House Price with Location

- Investigated how the location of a property influences its price with geographical analysis and visualisation.

**Key steps:**
- Plotted a Mapbox location and price visualisation, and a 3D scatter plot.
- Built and evaluated a linear regression model to predict house prices based on location.

#### 4. Predicting Price with Neighbourhood

- Analysed the impact of neighbourhood characteristics on house prices using Ridge regression to handle overfitting.

**Key steps:**
- Cleaned data, extracted neighbourhood information, and applied one-hot encoding.
- Built and evaluated the model, identifying significant neighbourhoods affecting house prices.

**Key Highlights:**

![Linear Regression Model Plot](images/project2/fig2.4_model_plot.png)
![Geographical Distribution of Housing Prices](images/project2/fig3.1_map.png)
![3D Scatter Plot with Plane](images/project2/fig3.3_3d.png)
![Feature Importance](images/project2/fig4.1_feature_importance.png)

---

## [Project 3: Cat Image Identification Using Deep Learning](https://github.com/alexzheng123/Cat_Image_Classification)

- Developed a deep neural network model to classify images as either containing a cat or not.
- Implemented a 5-layer neural network architecture using ReLU activations and sigmoid for the output layer.
- Trained on a dataset of 64x64 images and achieved over 98% accuracy on the training set and 82% on the test set.

### Key Steps

- **Data pre-processing**: Flattened, reshaped, and normalised input images.
- **Built the neural network**: [LINEAR->RELU] × (L-1) -> LINEAR -> SIGMOID.
- **Backpropagation**: Implemented gradient descent for weight updates.
- **Evaluation**: Tested the model on new images and visualised the results.
