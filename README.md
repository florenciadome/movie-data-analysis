# movie-data-analysis
Data analysis and visualization of a movie dataset to identify production and revenue trends.

# Movie Dataset Analytics

## Project Overview
This project presents an end-to-end exploratory data analysis (EDA) of a movie dataset obtained from Kaggle. The analysis focuses on identifying patterns, trends, and relationships in film production and global revenue over time using Python and data visualization techniques.

## Objectives
- Analyze a real-world tabular dataset with more than 10,000 records and multiple variables.
- Explore numerical and categorical features using Pandas.
- Apply statistical analysis with NumPy.
- Perform data cleaning and transformations.
- Create derived variables to enrich the analysis.
- Visualize distributions, comparisons, and trends.
- Answer research questions based on data-driven insights.

## Dataset
The dataset contains information about movies, including attributes such as release year, country, global sales, and production-related variables. It includes both numerical and categorical data and requires preprocessing due to missing values and variability.

Source:  
https://www.kaggle.com/datasets/mjshubham21/movie-dataset-for-analytics-and-visualization

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Google Colab

## Analysis Workflow

### 1. Initial Exploration
- Loaded the dataset using Pandas.
- Inspected dataset dimensions, data types, and missing values.
- Selected at least three numerical and three categorical variables for analysis.

### 2. Statistical Analysis with NumPy
- Converted selected columns to NumPy arrays.
- Calculated descriptive statistics (mean, median, standard deviation, percentiles).
- Implemented a custom function to automate statistical analysis.
- Normalized selected numerical variables.

### 3. Data Cleaning and Transformation
- Handled missing values by filling or removing them when appropriate.
- Grouped data by categorical variables to calculate averages and counts.
- Created new derived variables to support the analysis.

### 4. Data Visualization
- Distribution plots (histograms) to analyze production and sales over time.
- Comparative plots (boxplots and bar charts).
- Trend analysis using time-based visualizations.
- Advanced visualizations to highlight relationships and patterns.

## Research Questions and Findings

### 1. Were there periods of higher or lower film production?
Using the distribution plot from section 5.1, we analyzed the evolution of film production over time to identify periods of growth and decline. The analysis revealed clear variations in production levels across decades. Film production was lowest around 1950, while a significant increase was observed by 2020, reaching more than 80,000 movies produced.

### 2. How has global movie revenue evolved over time?
Based on the visualization in section 5.3, we examined the evolution of global movie revenue by release year. This analysis allowed us to identify record years, periods of stagnation, and significant declines. The highest peak in global revenue occurred during the 1950–1960 decade, while the most notable downturn was observed between the 1900–2000 period.

### 3. Which movies achieved the highest global sales and which countries produced them?
Using the comparative chart from section 5.2, we identified the movies with the highest global sales and their countries of origin. The analysis showed that the United States generated multiple peaks in global sales. Canada reached a record with the movie *“Single Idea”*, while Japan also achieved high global sales with *“Enjoy Assume”*, followed by the United Kingdom and Australia.

## Key Insights
- Film production has increased significantly over time, with notable growth in recent decades.
- Global movie sales present clear peaks and periods of decline that reflect historical and industry-related changes.
- Certain countries consistently dominate global sales, highlighting their strong presence in the film industry.

## Conclusions
This exploratory data analysis demonstrates how statistical analysis and visualization techniques can uncover meaningful historical trends and patterns in large real-world datasets. The results highlight the importance of data cleaning, transformation, and careful interpretation when analyzing complex data related to cultural and economic phenomena.

## Project Structure
- `data/`: Dataset used for the analysis  
- `notebooks/`: Google Colab notebook containing the full analysis
- `README.md`: Project documentation  

## Authors
This project was developed collaboratively by:
- Florencia Domé – Programming Student | Aspiring Data Analyst
- Micaela Bahurlet Goñi
- Carlos Spinetta

