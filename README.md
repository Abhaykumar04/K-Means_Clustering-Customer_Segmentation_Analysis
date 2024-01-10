

# K-Means Clustering: Customer Segmentation Analysis

### I. Introduction

1. **Objective**

   Perform customer segmentation analysis using K-Means Clustering on a Mall Customer dataset. Identify distinct groups based on features such as age, annual income, and spending score.

2. **Exploratory Data Analysis (EDA)**

   Utilize Python and libraries such as pandas, seaborn, and scikit-learn to explore, visualize, and preprocess the data.

### II. Dataset

   - Dataset: Mall Customers dataset containing information on age, annual income, and spending score.
   - File: 'Mall_Customers.csv'

### III. Exploratory Data Analysis

   - Visualize feature distributions using histograms.
   - Examine relationships between numerical variables with pair plots and correlation matrix heatmaps.

     <img width="521" alt="image" src="https://github.com/Abhaykumar04/K-Means_Clustering-Customer_Segmentation_Analysis/assets/112232080/c4b2e6f4-6c38-4070-8dc7-16a179130b90">


### IV. K-Means Clustering

   1. **Elbow Method**

      - Determine optimal cluster number using the Elbow Method to find the inertia value for different cluster sizes.
     
        <img width="966" alt="image" src="https://github.com/Abhaykumar04/K-Means_Clustering-Customer_Segmentation_Analysis/assets/112232080/e3a6809d-3d76-49e5-bd49-904c1f0a12b0">


   2. **Segmentation with K-Means**

      - Re-initialize K-Means algorithm with the identified optimal cluster number.
      - Visualize clusters and centroids in the age vs. spending score space.

      <img width="957" alt="image" src="https://github.com/Abhaykumar04/K-Means_Clustering-Customer_Segmentation_Analysis/assets/112232080/17b2348e-5e2e-421a-8def-57fb114b5928">

 
   3. **Cluster Analysis**

      - Assign cluster labels to each data point in the dataset.
      - Print segmented data for each cluster to understand customer characteristics.

### V. Results

   - **Cluster Visualization:**
     - Plot clusters in the annual income vs. spending score space, highlighting distinct customer segments.

### VI. Conclusion

   - K-Means Clustering reveals patterns in customer behavior, allowing for targeted marketing strategies and personalized customer engagement.

     <img width="476" alt="image" src="https://github.com/Abhaykumar04/K-Means_Clustering-Customer_Segmentation_Analysis/assets/112232080/14e172c6-f854-4216-a40b-8177dbdb242a">


### VII. Future Enhancements

   - Consider additional features for a more comprehensive segmentation.
   - Explore advanced clustering algorithms for comparison.
   - Implement dynamic cluster updating for real-time analysis.

### VIII. Acknowledgments

   - The project utilizes the Mall Customers dataset, and credit is given to the data source.
