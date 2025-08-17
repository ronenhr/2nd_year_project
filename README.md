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
# Preprocessing:
	•	Categorical encoding
	•	Missing value imputation
	•	Feature engineering (e.g., education-group, hour-type)
# Dimensionality Reduction:
	•	PCA – captures linear variance
	•	t-SNE – captures non-linear local structure for visualization
# Clustering Algorithms:
	•	K-Means – selected optimal k via Elbow method
	•	DBSCAN – epsilon estimated with k-distance graph
	•	Agglomerative Clustering – hierarchical insights
# Cluster Profiling:
	•	Mode and distribution analysis per cluster
	•	Visualizations (violin plots, count plots, PCA/t-SNE scatter plots)



 
