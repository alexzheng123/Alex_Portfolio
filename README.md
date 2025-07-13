# Alex's Portfolio

## Welcome!

Hi, welcome to my portfolio site! I'm Alex Zheng, an economics student with a passion for data science and machine learning. Here, you can find information about my projects.

---

## [Dissertation – Market Efficiency of Bitcoin in 2024](https://github.com/alexzheng123/EC331-project)

- Undergraduate dissertation analysing the weak-form market efficiency of Bitcoin using 1-minute BTC/USD data from 2024.
- Applied both traditional statistical tests (e.g. Ljung-Box, Hurst, BDS) and deep learning models (GRU, VMD-GRU-Attention).
- Proposed and tested a novel VMD-GRU-Attention model that achieved strong predictive performance in forecasting returns, challenging the weak-form EMH and suggesting that potentially exploitable trading opportunities may exist.

### Key Visualisations

#### Bitcoin Price & Volume (2024)
<img src="images/dissertation/Bitcoin Close Price and volume.png" width="600"/>

#### VMD-GRU-Attention Architecture
<img src="images/dissertation/VMD-GRU-Attention-steps.png" width="600"/>

#### VMD Decomposition
<img src="images/dissertation/VMD decomposition.png" width="600"/>

#### Forecast vs Actual (Validation & Test)
<div style="display: flex; gap: 10px;">
  <img src="images/dissertation/VMD-GRU-Att Forecast vs Actual Returns (Validation Set).png" width="48%"/>
  <img src="images/dissertation/VMD-GRU-Att Forecast vs Actual Returns (Test Set).png" width="48%"/>
</div>

---

## [Project 1: Hong Kong Housing Price Data Science Project](https://github.com/alexzheng123/Hong-Kong-Housing-Price)

- Scraped housing information from Centaline Property Agency.
- Cleaned and processed the data, including geocoding addresses.
- Conducted various visualisations and analyses to understand the housing market in Hong Kong.
- Investigated the influence of location and house size on property prices.

### Key Insights:

- Location has a more significant impact on house prices than size.
- Detailed visualisations of housing data on an interactive map.
- Statistical analysis revealing correlations between price and area.

### Key Highlights:

<div style="display: flex; justify-content: space-between;">
    <img src="images/project1/map_figure.png" alt="Geographical Distribution of Housing Prices" style="width: 45%;"/>
    <img src="images/project1/price_per_sq_foot_vs_area_scatter.png" alt="Price per Square Foot vs Area" style="width: 52%;"/>
</div>

---

## [Project 2: Buenos Aires Housing Price Prediction Project](https://github.com/alexzheng123/Buenos-Aires-Property-Market)

- Predicted housing prices in Buenos Aires using factors like size, location, and neighbourhood.
- Cleaned and prepared data, removing outliers and applying one-hot encoding for categorical features.
- Built multiple regression models (baseline, linear, and Ridge) across different dimensions.
- Visualised geographical price patterns using Mapbox and 3D scatter plots.
- Assessed model performance and identified influential neighbourhoods.

### Key Highlights

<div style="display: flex; justify-content: space-between;">
    <img src="images/project2/fig2.4_model_plot.png" alt="Linear Regression Model Plot" style="width: 23%;"/>
    <img src="images/project2/fig3.1_map.png" alt="Geographical Distribution of Housing Prices" style="width: 23%;"/>
    <img src="images/project2/fig3.3_3d.png" alt="3D Scatter Plot with Plane" style="width: 23%;"/>
    <img src="images/project2/fig4.1_feature_importance.png" alt="Feature Importance" style="width: 23%;"/>
</div>

---

## [Project 3: Cat Image Identification Using Deep Learning](https://github.com/alexzheng123/Cat_Image_Classification)

- Developed a deep neural network model to classify images as either containing a cat or not.
- Implemented a 5-layer neural network architecture using ReLU activations and a sigmoid output layer.
- Trained on a dataset of 64×64 images and achieved over 98% accuracy on the training set and 82% on the test set.

### Key Steps:

- Data pre-processing: Flattened, reshaped, and normalised input images.
- Built the neural network: [LINEAR → RELU] × (L−1) → LINEAR → SIGMOID.
- Backpropagation: Implemented gradient descent for weight updates.
- Evaluation: Tested the model on new images and visualised the results.
