### **A Machine Learning Framework for Early Asthma Diagnosis**

**Project motivation:** Asthma is a chronic lung condition that impacts roughly 300 million people worldwide across all ages, genders, and ethnic groups. Disadvantaged communities tend to have higher rates of the disease, highlighting the structural inequality to healthcare access. Implementing proactive strategies to address this issue will enhance health coverage while also easing the economic burden of disease on the U.S. government. This project’s goal is to create predictive models for early-onset asthma using social and socioeconomic factors in hopes to improve patient quality of life and reduce healthcare costs. I implemented four machine learning algorithms: Logistic Regression for simple comprehension of potentially linear patterns, CART for capturing non-linear patterns, XGBoost for handling any missing data, and Random Forests for handling complex patterns. The dataset used in the models includes anonymized patient demographics, medical history, and environmental factors. 

**Feature Selection:** To select features for model creation I used Variance Inflation Factor (VIF) and Principal Component Analysis (PCA). Features with a VIF below 5 were retained, resulting in 20 features.

**Model Selection:**
## 1. Logistic Regression
We decided to build a Logistic Regression model as it is the standard approach for binary classification tasks. It models the probability of the target variable (asthma diagnosis) being 1 (asthma) as a function of the independent variables, using a logistic function. Given the nature of our dataset and the binary classification problem, Logistic Regression was an appropriate starting point for our analysis.

## 2. Random Forest Classifier
The results from Logistic Regression led us to next build a Random Forests Classifier that combines multiple decision trees to improve classification performance. We hoped to capture an unseen complex relationship between features and target variables not found in Logistic Regression. 

## 3. Decision Tree (CART)
The results from the previous models were great at handling the majority class, but struggled with the minority class, so we decided to choose CART as the next step as it might handle it differently by recursively splitting the data based on feature thresholds. 

## 4. XGBoost
Finally, we chose XGBoost as it builds trees sequentially, where each new tree corrects the errors made by the previous one. For this reason, it was selected for its speed and efficiency with structured data, as well as its robust performance in predictive tasks. 

### 1. Suggest hypotheses about the causes of observed phenomena

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

```javascript
if (isAwesome){
  return true
}
```

### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
