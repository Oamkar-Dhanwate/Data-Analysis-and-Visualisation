# Data-Analysis-and-Visualisation 
---
1. Data Loading and Setup  
- Libraries Used: The notebook imports essential libraries, including `numpy`, `pandas`, `seaborn`, and `matplotlib`.  
- Dataset: Reads a CSV file named *"Instagram-Data.csv"* and renames its columns for easier reference. 
---

2. Exploratory Data Analysis (EDA)  
- Initial Inspection:  
  - Uses `df.info()` and `df.describe()` to summarize the dataset.  
  - Employs `sns.pairplot` to visualize relationships between numeric columns.  
- Country-Specific Analysis:  
  - Focuses on Instagram influencers targeting audiences in the United States and India.  
  - Plots bar charts to highlight top influencers and their follower counts for these countries.  
- Category-Based Analysis:  
  - Analyzes engagement and followers for influencers in the Music category.  
  - Barplots and pairplots visualize engagement averages and follower counts.  
- Correlation Analysis:  
  - Computes and visualizes a correlation matrix for numerical features using a heatmap.  

---

3. Advanced Data Analysis  
- Engagement Analysis:  
  - Sorts influencers by engagement average and creates visualizations of the top performers by country and category.  
---

4. Machine Learning Models  
- Influencer Classification:  
  - Defines influencer types (Micro, Macro, and Mega) based on follower count.  
  - Encodes categorical variables using `LabelEncoder`.  
  - Trains a `RandomForestClassifier` to classify influencers by type based on followers, engagement average, and engagement ratio.  
  - Evaluates the model using accuracy and classification reports.  
  - Predicts influencer types for new data inputs.  
- Engagement Prediction:  
  - Builds a linear regression model to predict engagement averages from follower counts.  
  - Prepares data with dummy variables for categorical features.  
  - Evaluates the regression model using metrics like Mean Squared Error (MSE) and R-squared.  
  - Visualizes the model's predictions against actual engagement values.  
  - Predicts engagement for new follower counts.  
---

5. Visualization Highlights  
- Extensive use of bar plots, scatter plots, and pair plots to present insights.  
- A correlation heatmap to identify relationships among numerical features.  
- Detailed customization of plots, including labels, titles, and bar annotations.  
---

Key Features  
1. Country-Specific Insights: Analyzes influencer distribution and engagement trends by audience country.  
2. Category-Specific Trends: Highlights engagement differences across categories like Music.  
3. Machine Learning:  
   - Classification: Identifies influencer types.  
   - Regression: Predicts engagement averages based on follower counts.  
---
