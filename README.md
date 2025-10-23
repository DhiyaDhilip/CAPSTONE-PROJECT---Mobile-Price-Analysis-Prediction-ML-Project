# CAPSTONE-PROJECT---Mobile-Price-Analysis-Prediction-ML-Project
This capstone project analyzes mobile phone listings from Amazon India using web scraping, data cleaning, and visualization. It applies clustering, classification, and regression to uncover pricing patterns and predict mobile prices based on RAM, storage, and ratings. The model is optimized and deployed for real-time predictions.

Absolutely, Sandhiya! Here's a **stylized, energetic version** of your **Mobile Price Analysis & Prediction** project description — perfect for showcasing in a portfolio, resume, or presentation with flair:


##  CAPSTONE PROJECT: Mobile Price Analysis & Prediction

###  What’s the Mission?
To decode the pricing secrets of mobile phones using real-time Amazon data. From scraping product specs to predicting prices with machine learning — this project blends data engineering, analytics, and AI into one powerful pipeline.

###  Workflow Highlights:
1. ** Data Collection**: Scraped mobile listings from Amazon using BeautifulSoup — captured names, prices, ratings, RAM, and storage.
2. ** Data Cleaning**: Transformed messy specs into clean numeric features. Filtered out invalid entries and missing values.
3. ** Visual Insights**:
   - Price distribution histogram
   - Rating vs Price scatter plot
   - Boxplot of ratings by price category
4. ** Clustering**: Grouped mobiles into 3 clusters using KMeans based on specs — revealed hidden market segments.
5. ** Classification**: Trained a Random Forest Classifier to categorize mobiles into **Low**, **Medium**, and **High** price bands.
6. ** Regression Modeling**:
   - Used TF-IDF to extract brand/name features
   - Combined with RAM, Storage, Rating
   - Tuned Random Forest Regressor with GridSearchCV
   - Predicted actual mobile prices with high accuracy
7. ** Feature Importance**: Visualized which specs and brand signals drive price the most.

   <img width="1080" height="681" alt="image" src="https://github.com/user-attachments/assets/a20f8229-a832-4f6e-abb2-a1c7f79b53a2" />
   <img width="1130" height="684" alt="image" src="https://github.com/user-attachments/assets/eec59564-a9ec-4a1e-9fbf-5d7796afacf9" />
   <img width="1151" height="688" alt="image" src="https://github.com/user-attachments/assets/923765d2-4d6b-4fe5-a706-ee9c5896e6c1" />
   <img width="753" height="571" alt="image" src="https://github.com/user-attachments/assets/d94c5d2c-37c8-4251-8297-95af8d913880" />
   <img width="1157" height="661" alt="image" src="https://github.com/user-attachments/assets/f5ce3683-ff22-437b-b58c-b980d8eb6ba4" />




###  Tech Stack:
- **Python**: Core engine
- **Libraries**: BeautifulSoup, Pandas, Scikit-learn, Matplotlib, Seaborn
- **ML Models**: Random Forest (Classifier & Regressor), KMeans
- **Text Features**: TF-IDF Vectorizer

###  Bonus:
- Predicted price for a new sample: *Samsung Galaxy M14 5G 8GB RAM 128GB Storage*
- Saved model for future deployment
- Verified feature importance for explainability

###  Outcome:
A full-stack ML pipeline that scrapes, cleans, visualizes, clusters, classifies, and predicts mobile prices — ready for deployment or integration into a pricing engine or e-commerce dashboard.


