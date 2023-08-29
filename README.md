# machine_learning_project-unsupervised-learning

## Project Outcomes
- The project outcome is to classify or segment the customer into groups so that we can use that data for other business plans.
### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

#### Project structure
The project has two main files: `Wholesale_Data.csv` and the notebook `Unsupervised Learning.ipynb`
The presentation file `MLUnsupversisedLearningPresentationFile_EthanLam.pdf` is for presenting the process and output.

#### The project process
##### EDA
- Handling missing values
- Handling duplicated values
- Handling outliers
- Data visualization

##### Scaling
- Handling scaling data using Standard Scaler


##### KMeans clustering
- Use Elbow method to find the optimal clustering
- Apply optimal clustering to find cluster number for each datapoint

##### Hierrachy
- Use Dendogram method to find the optimal clustering
- Apply optimal clustering to find the cluster number for each datapoint

##### PCA
- Use Explained variance ratio to find the features that has most information
- Ploting the class separation using the principal components founded

##### Conclusion
- By using Clustering, we can classify customer into specific groups so that as a company, it is good for them to address the need of each groups precisely
