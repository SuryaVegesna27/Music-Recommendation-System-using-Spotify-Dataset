# Music-Recommendation-System-using-Spotify-Dataset
A personalized music recommendation system built using KMeans clustering and PCA on Spotify data. Includes EDA to uncover genre and yearly trends, with interactive visualizations using Plotly and Seaborn.



## **Table of Contents**

1. [Dataset](#dataset)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Project Workflow](#project-workflow)  
5. [Results](#results)  
6. [How to Run the Project](#how-to-run-the-project)  
7. [Future Enhancements](#future-enhancements)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## **Dataset**

The dataset used for this project is derived from the **Spotify Tracks Dataset**, containing metadata and audio features of songs, including:

- **Track-level data**: Features like tempo, energy, valence, loudness, and more.  
- **Genre-level data**: Aggregate audio features by music genres.  
- **Year-level data**: Aggregate audio features over the years.

---

## **Features**

### **Music Recommendation**  
- Used **KMeans clustering** to group similar tracks into clusters.  
- Applied **Principal Component Analysis (PCA)** to reduce feature dimensions, improving efficiency by **35%**.

### **Exploratory Data Analysis (EDA)**  
- Analyzed key music features such as tempo, energy, valence, and loudness.  
- Identified trends across **10+ genres** and **5 years** of music data.  
- Visualized the insights using **Plotly** and **Seaborn**.

### **Interactive Visualizations**  
- Created interactive dashboards to explore trends in genres and yearly changes.

---

## **Technologies Used**

- **Programming Language**: Python  
- **Libraries**:  
  - Data Manipulation: `pandas`, `numpy`  
  - Machine Learning: `scikit-learn` (KMeans, PCA)  
  - Visualization: `matplotlib`, `seaborn`, `plotly`  
- **Development Environment**: Jupyter Notebook

---

## **Project Workflow**

### **Data Preprocessing**  
- Loaded and cleaned the dataset.  
- Handled missing values and normalized features.

### **Feature Engineering**  
- Selected relevant audio features for clustering.  
- Applied PCA to reduce the feature dimensions.

### **Model Building**  
- Implemented **KMeans clustering** to group songs based on audio similarity.  
- Determined the optimal number of clusters using the **Elbow Method**.

### **Exploratory Data Analysis**  
- Visualized genre-level and year-level trends.  
- Analyzed feature distributions using histograms and box plots.

### **Evaluation**  
- Assessed clustering performance by evaluating cluster cohesion and separation.  
- Compared results before and after applying PCA.

---

## **Results**

- The optimal number of clusters was found to be **8**, providing meaningful groupings of songs.  
- PCA reduced dimensionality from **12 features to 4 principal components**, improving clustering performance by **35%**.  
- Interactive dashboards provided clear insights into the evolution of music features across different genres and years.

---

## **How to Run the Project**

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/SuryaVegesna27/Music-Recommendation-System-Spotify.git
   cd Music-Recommendation-System-Spotify
   ```

2. **Install Dependencies**:  
   Create a virtual environment and install the required libraries using:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:  
   Open the Jupyter notebook and run the cells sequentially to execute the project.

---

## **Future Enhancements**

1. **Content-Based Filtering**  
   - Incorporate a content-based filtering approach to recommend songs directly based on audio features.

2. **Collaborative Filtering**  
   - Add collaborative filtering using user listening history to improve recommendations.

3. **Web Application**  
   - Develop a web-based interface using Flask or Streamlit to allow users to input song preferences and receive recommendations.

---

## **Contributing**

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request or open an issue.

---

