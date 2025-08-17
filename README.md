# 2nd_year_project
Income Clustering Project

This project explores clustering techniques on the Adult Income Census dataset to identify meaningful groups of individuals based on demographics, education, work patterns, and income.
The goal is to uncover patterns that can help policymakers, researchers, or businesses better understand socioeconomic segments.

# Project Overview
	•	Dataset: UCI Adult Income Census
	•	Objective: Apply unsupervised learning (clustering) to group individuals into interpretable clusters.
	•	Focus: Education, workclass, occupation, hours worked, and income.

We tested multiple clustering techniques and dimensionality reduction approaches to ensure robust insights.

# Methods
## Preprocessing:
	•	Categorical encoding
	•	Missing value imputation
	•	Feature engineering (e.g., education-group, hour-type)
## Dimensionality Reduction:
	•	PCA – captures linear variance
	•	t-SNE – captures non-linear local structure for visualization
## Clustering Algorithms:
	•	K-Means – selected optimal k via Elbow method
	•	DBSCAN – epsilon estimated with k-distance graph
	•	Agglomerative Clustering – hierarchical insights
## Cluster Profiling:
	•	Mode and distribution analysis per cluster
	•	Visualizations (violin plots, count plots, PCA/t-SNE scatter plots)

# Key Insights
## Education–Income Link:
	•	Income >50K is dominated by individuals with Bachelor’s or higher.
	•	Groups with Less than HS almost exclusively fall in the <=50K bracket.
## Occupation–Work Hours Patterns:
	•	Clerical, Sales, Service → stable full-time with little overtime.
	•	Exec/Managerial & Professional → more spread into overtime and extreme hours.
	•	Farming/Fishing → highly skewed to extreme working hours.
## Workclass–Education:
	•	Private sector shows broad spread but peaks at HS-grad / Some-college.
	•	Government & Self-employed lean more toward Bachelor’s or higher.
## Clustering Results:
	•	K-Means with k=3 gave clear, interpretable groupings.
	•	DBSCAN helped identify outliers and smaller niche groups.
	•	Agglomerative confirmed hierarchical separation by education and occupation.

# How to Run
1.	Clone the repository
 git clone https://github.com/ronenhr/2nd_year_project.git
cd your-repo-name

2.	Create a virtual environment (optional but recommended)
   
	python -m venv venv

	source venv/bin/activate   # Mac/Linux

	venv\Scripts\activate      # Windows

4.	Install dependencies
   
	pip install -r requirements.txt

6.	Run the notebooks
   
	jupyter notebook

 
