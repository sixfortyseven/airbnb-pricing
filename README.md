# Airbnb Pricing Analysis
This project analyzes Airbnb listing data from a major metropolitan area to uncover the key drivers of nightly pricing, identify natural groupings of listings, and deliver actionable insights for hosts, platform operators, and consumers.

## Business Objective
- Understand the key drivers of **nightly pricing** for Airbnb listings.
- Identify **natural groupings** (clusters) of listings that align with consumer market segments (e.g., budget, family, luxury).
- Deliver actionable insights that could be used by hosts, platform operators, or consumers.

## Dataset
- **Source:** 3,982 Airbnb listings
- **Features:** Property type, host attributes, location score, review score, amenities, pricing, and more
- **Objective:** Explore factors influencing nightly rates and segment listings into meaningful clusters

## Project Structure

**1. Data Exploration & Cleaning**
  - Load raw Airbnb listing data
  - Handle missing values, outliers, and inconsistent formats
  - Feature engineering (e.g., extract amenities, encode categorical variables)
  - Generate summary statistics and initial visualizations

**2. Exploratory Data Analysis (EDA)**
  - Visualize distributions of key features (price, location score, review score, etc.)
  - Analyze relationships between variables using scatter plots, boxplots, and correlation matrices
  - Identify patterns and anomalies in the data

**3. Statistical Analysis**
  - Perform hypothesis testing **(ANOVA, t-tests)** to compare pricing across property types, seasons, and other categories
  - Assess statistical significance of observed differences

**4. Predictive Modeling**
  - Build and evaluate **linear regression models** to predict nightly price
  - Develop **decision tree regression models** to capture nonlinear relationships
  - Compare model performance using metrics like RMSE and R²
  - Conduct model diagnostics (residual analysis, cross-validation)

**5. Model Interpretation**
  - Analyze feature importance from tree-based models
  - Use **SHAP values** to interpret individual predictions
  - Generate partial dependence plots to visualize feature effects

**6. Cluster Analysis**
  - Apply **KMeans clustering** to segment listings into market groups
  - Use **PCA** for dimensionality reduction and cluster visualization
  - Profile clusters based on key features (e.g., price, amenities, location)

**7. Summary & Conclusions**
  - Synthesize findings from analysis and modeling
  - Discuss business implications for hosts, platform operators, and consumers
  - Outline limitations and propose next

## Key Insights
- **Property type, season, location score, and review score** are major pricing drivers
- **Decision tree models** reveal nonlinear effects and feature interactions missed by linear regression
- **Cluster analysis** enables targeted pricing and marketing strategies