# Spotify-clustering
Spotify Song Genre Clustering
Overview
This project focuses on clustering Spotify song genres using the Bradley-Fayyad-Reina (BFR) clustering algorithm, implemented from scratch. The Spotify Songs dataset is used to explore genre patterns by grouping songs based on their features. To evaluate clustering performance, a cross-tabulation accuracy approach is applied, and the results are visualized with t-SNE (t-Distributed Stochastic Neighbor Embedding) for dimensionality reduction.

Features
Custom BFR Algorithm Implementation: Efficiently clusters high-dimensional data.
Spotify Songs Dataset: Includes detailed features such as tempo, loudness, and energy.
Performance Evaluation: Uses cross-tabulation for accuracy assessment.
Visualization: Leverages t-SNE for a 2D representation of clusters.
Technologies
Python
NumPy
Pandas
Matplotlib/Seaborn
Scikit-learn

Installation
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/spotify-bfr-clustering.git  
cd spotify-bfr-clustering  
Install dependencies:

bash
Copy code
pip install -r requirements.txt  
Download the dataset (if not included) and place it in the data/ folder.

Usage
Preprocess the Dataset:
Run the script to clean and normalize the data:

bash
Copy code
python src/data_preprocessing.py  
Run BFR Clustering:
Execute the clustering algorithm:

bash
Copy code
python src/bfr_clustering.py  
Evaluate Accuracy:
Generate cross-tab accuracy metrics:

bash
Copy code
python src/evaluation.py  
Visualize Results:
Create 2D visualizations using t-SNE:

bash
Copy code
python src/visualization.py  
Results
Clustering Accuracy: The clustering performance is evaluated using cross-tabulation to measure the alignment between predicted clusters and actual genres.
t-SNE Visualization:

(Replace this placeholder with your generated t-SNE plot.)
Future Work
Optimize the BFR algorithm for larger datasets.
Experiment with additional clustering methods.
Incorporate more advanced evaluation metrics.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Spotify for the dataset.
Community resources for clustering algorithms and visualizations.
