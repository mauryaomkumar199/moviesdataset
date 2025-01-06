# moviesdataset

**Dataset Overview and Loading**
Loaded the movies dataset using Python libraries like pandas and numpy.
Conducted an initial inspection to understand the dataset structure, including:
Columns, data types, and summary statistics.
Missing values and outliers.

**Data Cleaning**
Removed unwanted fields irrelevant to the analysis.
Handled missing/null values:
Categorical columns (e.g., genre, directors, writers) were imputed with placeholders or the mode.
Numerical columns (e.g., runtime_in_minutes, audience_rating) were filled using statistical techniques like median imputation.
Date columns (in_theaters_date, on_streaming_date) were imputed with placeholder dates.

**Exploratory Data Analysis**
Visualized and analyzed key trends and relationships:
Box Plots: Showed the distribution of audience ratings across different genres.
Histograms: Explored the frequency distribution of audience ratings.
Pie Charts: Displayed the proportion of movies in different genres.
Frequency Plots: Highlighted the count of movies by rating categories.
Calculated statistics like the correlation between audience_rating and tomatometer_rating.
Grouped data to identify top-performing genres and the average audience rating by genre.

**Key Insights**
Genres with the highest average audience ratings.
Performance trends of movies released over time.
Distribution and trends in audience ratings, highlighting potential rating bins for classification.

**Predictive Modeling with Logistic Regression**
Objective: Build a model to classify audience ratings (rating_bin).
Preprocessing:
Selected key features (runtime_in_minutes, tomatometer_rating, audience_rating).
Standardized numerical features using StandardScaler.
Encoded categorical variables where necessary.

**Model Training**
plit the dataset into training and testing sets (80:20 ratio).
Trained a Logistic Regression model with multi-class classification enabled.

**Evaluation**
Achieved a model accuracy of 95%.
Generated a detailed classification report showcasing precision, recall, and F1-score.
Visualized confusion matrix and performance metrics to validate results.

**Results**
The project improved my ability to handle real-world datasets by addressing challenges like missing values and diverse data types.
Learned to generate insightful visualizations that communicate trends effectively.
Built a high-performing classification model with 95% accuracy, demonstrating expertise in model selection and evaluation.

**Conclusion**
This project sharpened my skills in EDA, data cleaning, visualization, and predictive modeling. It reinforced the importance of understanding data trends before applying machine learning models. The combination of domain understanding and technical skills allowed me to deliver impactful results.
