# ML---Predicting-Global-Video-Game-Sales

## Introduction
In this report, I explore the application of linear logistic regression to predict the global sales of video games based on its platform, genre, publisher and other factors. The dataset was acquired from Kaggle. Heres the link to the dataset: https://www.kaggle.com/datasets/gregorut/videogamesales.
The dataset contains information about video game sales, including attributes such as platform, genre, publisher and regional sales figures.

## Research Question 
The primary research question driving this analysis is whether we can accurately predict the global sales of video games based on their regional sales figures? This question aims to explore the relationship between various factors and global sales performance in the video game industry.

## Cleaning the Data
In the data cleaning phase, several steps were taken to ensure the dataset’s integrity and usability for analysis. 
Null values were removed from the dataset using methods such as dropping rows with missing values or imputing missing values if applicable. Columns that were not relevant to predicting global sales, such as ‘rank’ and ‘name’, were dropped from the dataset to streamline the analysis. The rationale behind each data cleaning step was to improve the quality and relevance of the data for subsequent analysis.


## Graphing Data
In this section, various visualizations were created to explore the relationships between different variables in the dataset. Each graph was accompanied by a brief description highlighting its purpose and key insghts.
Graph 1: Platform vs Global Sales
The scatter plot shows the relationship between video game platforms and their corresponding global sales. It helps identify which platforms have higher sales.


### Graph 1: Platform vs Global Sales
The scatter plot shows the relationship between video game platforms and their corresponding global sales. It helps identify which platforms have higher sales.

![image](https://github.com/Mr-Gabby/ML---Predicting-Global-Video-Game-Sales/assets/101271219/6211253e-2ee4-422c-ba8f-3cdfef478d12)


### Graph 2: Genre vs Global Sales
This bar chart illustrates the distribution of video game genres and their respective global sales. It provides insights into which genres are more popular among gamers.

![image](https://github.com/Mr-Gabby/ML---Predicting-Global-Video-Game-Sales/assets/101271219/d17cda6d-9253-4b26-9062-7d9b2c6ed64a)

## Graph 4: Year vs Global Sales
This line plot showcases the trend of global video game sales over thr years. It highlights any significant changes or patterns in sales performance.

![image](https://github.com/Mr-Gabby/ML---Predicting-Global-Video-Game-Sales/assets/101271219/e7fbcc0e-df1a-4612-ba0e-50ab0595050e)

## Graph 5: Regional Sales Comparison
This box plot compares the distribution of sales across different regions (e.g., North America, Europe, Japan, Others). It provides insights into regional sales variations.

![image](https://github.com/Mr-Gabby/ML---Predicting-Global-Video-Game-Sales/assets/101271219/cb357b17-e0d9-480f-8a6c-37b49c90c41b)


## Evaluating the Model
Model evaluation was performed using mean squared error (MSE) as the performance metric. MSE measures the average squared difference between the actual and predicted values, providing insight into the model's accuracy in predicting global sales. The evaluated model's performance was analyzed to determine its effectiveness in capturing the variability in global sales and identifying any potential areas for improvement. The MSE value was 2.7205096141254305e-05 indicating that the model’s prediction are quite accurate, with low average squared deviation from the actual values.

## Conclusion
Based on the analysis and model evaluation, we can conclude that while the linear regression model provides some predictive capability for global sales, there may be other factors not captured in the dataset that influence sales performance. The question of accurately predicting global sales of video games remains challenging, and further research and refinement of models are needed to improve predictive accuracy. Nevertheless, this analysis provides valuable insights into the factors affecting video game sales and lays the foundation for future studies in this area.









