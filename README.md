Wholesale Customers Data Analysis & Clustering
This project explores unsupervised machine learning techniques to analyze and segment wholesale customers based on their annual spending patterns. Multiple clustering algorithms are applied and compared to understand customer behavior and identify meaningful groups.

📌 Project Overview
The notebook performs customer segmentation using the Wholesale Customers Dataset, applying:
K-Means Clustering
Hierarchical (Agglomerative) Clustering
DBSCAN
Dimensionality reduction and evaluation metrics are used to visualize and assess clustering performance.

📊 Dataset
Dataset: Wholesale Customers Data
Features: Annual spending on product categories such as Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicassen
Type: Numerical, multivariat
Use case: Customer segmentation and pattern discovery

⚙️ Techniques Used
1. Data Preprocessing
Handling scale differences using StandardScaler
Outlier detection using Z-score
Dimensionality reduction with PCA

3. Clustering Algorithms
K-Means
Elbow Method
Silhouette Score
Hierarchical Clustering
Dendrogram visualization
Agglomerative Clustering

4.DBSCAN
Density-based clustering
Noise/outlier detection

3. Evaluation & Visualization
Silhouette Score
2D PCA visualizations
Cluster plots using Matplotlib & Seaborn

🛠️ Technologies & Libraries
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
SciPy

📁 Project Structure
├── Wholesale customers data_analysis.ipynb
├── README.md

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project folder:
cd your-repo-name
Open the notebook:
jupyter notebook
Run all cells in Wholesale customers data_analysis.ipynb

📈 Results & Insights
Identified distinct customer segments based on purchasing behavior
Compared strengths and weaknesses of different clustering algorithms
Visualized customer groups in reduced dimensions for better interpretation

📌 Conclusion

This project demonstrates how different clustering techniques can be applied to real-world customer data to extract actionable insights. The comparison highlights how algorithm choice affects segmentation results.

📬 Contact
Rushikesh Jadhav
If you have any questions or suggestions, feel free to connect!
