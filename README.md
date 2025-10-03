# 🎬 Netflix Movie Data Analysis

This project analyzes a dataset of Netflix movies and TV shows to explore insights such as popularity, genres, vote averages, and release year distributions.  
It is a beginner-friendly data analysis project created in Python using Jupyter Notebook.

---

## 📂 Project Files
- **Netflix_Movie_Analysis.ipynb** → Main Jupyter Notebook with analysis and visualizations  
- **requirements.txt** → Python libraries required to run the notebook  
- **data source** → Dataset is loaded directly from [this CSV on GitHub](https://raw.githubusercontent.com/TheiScale/YouTube-Video-Notes/refs/heads/main/New%20Netflix%20Data%20Analysis%20Project%202025/mymoviedb.csv)  

---

## 🔧 Tools & Libraries Used
- Python  
- Pandas → Data manipulation and cleaning    
- Matplotlib & Seaborn → Data visualization  
- Jupyter Notebook  

---

## 📊 Key Steps in the Analysis
1. **Data Loading**  
   - Loaded the dataset containing 9 columns and 9827 rows.  

2. **Data Cleaning & Preprocessing**  
   - Checked for null and duplicate values (none found).  
   - Converted `Release_Date` into datetime and extracted release year.  
   - Dropped less useful columns: `Overview`, `Original_Language`, `Poster_Url`.  
   - Handled `Genre` column by splitting comma-separated values and exploding them into individual rows.  
   - Converted `Genre` into categorical data type.  

3. **Feature Engineering**  
   - Created new column `Release_year`.  
   - Categorized `Vote_Average` into 4 groups:  
     - **Not Popular**  
     - **Below Average**  
     - **Average**  
     - **Popular**  

4. **Exploratory Data Analysis (EDA)**  
   - Checked distribution of vote categories.  
   - Visualized vote averages with `Seaborn`.  
   - Identified the movie with the **highest popularity** and its genre.  


---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/netflix-movie-analysis.git
