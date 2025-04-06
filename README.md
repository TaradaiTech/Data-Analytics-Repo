# Movies Data Analysis Project  
<div align="right">
  <img src="https://github.com/TaradaiTech/Data-Analytics-Repo/blob/main/Catgif.gif" alt="Cat GIF" style="width: 100px;">
</div>                                           

## Overview
In this project, I embarked on an exploratory data analysis (EDA) journey to understand the factors driving movie success. I automated the process of data cleaning, visualization, and insight extraction, creating interactive and insightful visualizations that help identify patterns between features like movie budgets, gross earnings, ratings, and more.

---

## Tools & Technologies Used

Python: The backbone of this project. Python’s flexibility allowed me to efficiently handle large datasets, automate data cleaning, and implement advanced visualizations and statistical analyses.
- Libraries like Pandas and NumPy were used for data manipulation and handling missing values.
- Seaborn and Matplotlib were leveraged to create rich visualizations, ensuring clarity and appeal. The seaborn.regplot and pairplot functions were particularly useful for displaying relationships between variables in a clean, interpretable manner.
Jupyter Notebook: Ideal for this data science project, Jupyter enabled me to seamlessly combine code, visualizations, and explanations in a readable format, which is essential for iterative analysis.
Scikit-learn: For predictive modeling, I implemented linear regression to predict movie earnings based on factors like budget, votes, runtime, and more. Train-test split and evaluation metrics (RMSE, R² score) helped assess model performance.

---

## What I Learned

Automating Data Cleaning: This was a key focus of the project. I developed strategies for cleaning datasets, such as handling missing values and ensuring correct data types. Through this, I understood the importance of data integrity in achieving meaningful analysis.

Exploratory Data Analysis (EDA): I learned how to apply statistical methods (e.g., Pearson correlation) and visualization tools to uncover relationships in the data. This helped me dive deep into how budget influences gross earnings and the distribution of movie scores across different genres.

Outlier Detection: By implementing the Interquartile Range (IQR) method, I gained insights into data quality and learned how to handle extreme values that might distort analysis.

Visualization Mastery: The project honed my ability to convey complex patterns through visualizations. I learned to use scatter plots, regression plots, and pairplots to represent data insights in an easily interpretable way. Violin plots allowed me to delve into the distribution of scores across movie ratings.

Predictive Modeling: I ventured into predictive analytics, applying linear regression to predict movie success based on various factors. Understanding model performance through metrics like RMSE and R² score was a significant milestone, as I learned to evaluate the accuracy and potential of my predictions.

---

## Key Takeaways

Data-driven Decision Making: By automating the data cleaning process and providing actionable insights through visualizations, I was able to showcase how data analysis can inform business strategies (e.g., budget allocation for movie productions).
Importance of Data Visualization: I discovered that the right visual representation can transform raw data into a compelling story, making the analysis accessible and understandable to stakeholders without technical backgrounds.

---

## Why I Chose These Tools

Python provides unmatched flexibility and scalability, making it my go-to language for data analysis projects.
Pandas made data manipulation straightforward, while NumPy ensured efficient numerical computations.
Matplotlib and Seaborn allowed me to craft clear and engaging visualizations with minimal code.
Scikit-learn was essential for implementing predictive models and assessing their effectiveness.

---

### Final Thoughts

#### This project was a fulfilling experience where I not only enhanced my technical skills but also deepened my appreciation for the power of data in storytelling. By combining automation, statistical analysis, and compelling visualizations, I was able to extract valuable insights that can drive smarter decisions in industries like entertainment.

---
    
# Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python libraries (install via `pip install -r requirements.txt`)

### Data Acquisition
**Note:** The dataset used in this project is sourced from Kaggle.  
Due to licensing restrictions and file size considerations, the raw dataset is not included in the repository. Instead, please follow these steps:
1. Visit the [Kaggle Movies Dataset page](https://www.kaggle.com/datasets/danielgrijalvas/movies).
2. Download the dataset and place the CSV file in a folder named `data/` at the root of this repository.
3. Ensure the file path in the notebook corresponds to the location of the CSV file (e.g., `data/movies.csv`).

## Project Structure
- **notebook.ipynb**: The main Jupyter Notebook containing all the analysis steps, code, and commentary.
- **README.md**: This file, which provides an overview of the project.
- **requirements.txt**: A list of Python dependencies required to run the notebook (e.g., pandas, numpy, seaborn, matplotlib, scikit-learn).
  
### Running the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/LetMeCodeNow-Githob/Data-Analytics-Repo.git
