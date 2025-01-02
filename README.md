### Song Success Predictability 📀🎶

---

#### **Introduction**
This project focuses on predicting the success of songs using Spotify data spanning decades. By leveraging audio features such as danceability, energy, loudness, and valence, the project aims to classify tracks as "hits" or "flops" and uncover the characteristics that contribute to a song's popularity. Using machine learning models and exploratory data analysis, this research provides insights for music professionals seeking data-driven strategies for creating chart-topping tracks.

---

#### **Objective**
To develop a predictive model that analyzes audio features to classify songs as "hits" or "flops," offering actionable insights into the factors influencing song success across decades.

---

#### **SMART Questions**
1. Which audio features are most strongly associated with hit songs in this dataset?
2. How do feature trends vary across decades (e.g., 1960s vs. 2010s)?
3. Can we build an accurate predictive model for song success using machine learning?
4. What social factors (e.g., danceability, energy) influence the likelihood of a song being a hit?
5. How does genre impact a song's potential to succeed?

---

#### **Dataset**
- **Source**: Spotify API and Kaggle Dataset ([Link to Dataset](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset?select=dataset-of-00s.csv))
- **Key Features**:
  - Audio Attributes: Danceability, Energy, Loudness, Acousticness, Valence, etc.
  - Metadata: Track Name, Artist, URI, Duration, Key, Mode, etc.
  - Target Variable: Hit (1) or Flop (0)
- **Preprocessing**:
  - Addressed missing values, duplicates, and imbalanced classes.
  - Conducted feature scaling and encoding for machine learning compatibility.

---

#### **GitHub Repository**
Find the complete project code, documentation, and visualizations here: [GitHub Repository](https://github.com/AshwinMuthuraman/Team4Project_DATS6103_10)

---

#### **Key Findings/Conclusion**
1. **Feature Insights**:
   - Key predictors include **danceability**, **loudness**, **acousticness**, and **valence**.
   - Hit songs tend to be louder, more energetic, and danceable, with shorter durations.
   
2. **Model Performance**:
   - **Best Model**: Support Vector Machines (RBF Kernel) with hyperparameter tuning.
   - **Accuracy**: 85%
   - **AUC**: 91%, showcasing strong predictive capability.

3. **Impact of Decades**:
   - Musical preferences and feature trends vary significantly over time, reflecting evolving audience tastes.

4. **Conclusion**:
   - Predictive models based on audio features are effective in distinguishing hits from flops.
   - These insights can guide music producers, artists, and industry stakeholders in crafting data-driven strategies for success.

--- 
