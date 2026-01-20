

# 🎬 Netflix Recommendation Engine – Capstone Project

## 📌 Project Overview
This project simulates a **movie recommendation engine** using a synthetic Netflix‑style dataset. It explores genre popularity, builds predictive models to recommend movies to users, and identifies the best and worst rated genres. The project demonstrates how machine learning can be applied to recommendation systems.

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas, NumPy** – data manipulation
- **Matplotlib** – visualizations
- **Scikit‑Learn** – machine learning models (Linear Regression, Decision Tree, Random Forest)

---

## 🔍 Objectives
1. **Most Popular and Liked Genres**  
   - Identify genres with the highest number of ratings  
   - Calculate average ratings per genre  

2. **Movie Recommendation Model**  
   - Train ML models (Linear Regression, Decision Tree, Random Forest)  
   - Predict ratings for unrated movies per user  
   - Recommend top movies per user and genre  

3. **Best and Worst Rated Genres**  
   - Compute average ratings and total ratings per genre  
   - Highlight best and worst performing genres  

---

## 📈 Workflow
1. **Dataset Creation**
   - Synthetic dataset of 10 movies across genres (Action, Comedy, Drama, Horror)  
   - 20 users with random ratings (1–5 scale, ~70% coverage)  

2. **Exploratory Analysis**
   - Genre popularity (number of ratings)  
   - Genre average ratings  

3. **Model Training**
   - Features: `user_id`, `movie_id`, `genre_encoded`  
   - Models: Linear Regression, Decision Tree, Random Forest  
   - Evaluation: Mean Squared Error (MSE)  

4. **Recommendations**
   - Predict ratings for unrated movies  
   - Recommend top 3 movies per user (optionally filtered by genre)  

5. **Genre Analysis**
   - Best and worst rated genres  
   - Visualization of average ratings per genre  

---

## 📊 Key Insights
- **Most Popular Genre:** Based on number of ratings  
- **Best Rated Genre:** Highest average rating  
- **Worst Rated Genre:** Lowest average rating  
- **Best ML Model:** Selected based on lowest MSE  
- **Dataset Stats:**  
  - Total Movies: 10  
  - Total Users: 20  
  - Total Ratings: ~140+ (randomized)  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-recommendation-engine.git
   cd netflix-recommendation-engine
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Run the script:
   ```bash
   python netflix_recommendation.py
   ```

---

## 📌 Future Improvements
- Expand dataset with real Netflix‑like data  
- Add collaborative filtering (Matrix Factorization, SVD)  
- Integrate deep learning models for recommendations  
- Build an interactive dashboard with Streamlit or Plotly  

