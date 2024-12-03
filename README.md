## Sentiment-Driven-Passenger-Segmentation-of-Airlines
# Data Collection
Passenger reviews were scraped from Skytrax using Python tools (e.g., BeautifulSoup, Selenium). The dataset includes attributes like review text, ratings, and traveler demographics. Reviews were stored in CSV format for preprocessing and analysis.
# Data Preprocessing
To ensure data quality:

Filtering: Non-verified reviews, duplicates, and rows with missing values were removed.
Text Normalization: Reviews were standardized by lowercasing, removing punctuation, and eliminating stopwords.
Encoding: Categorical variables (e.g., traveler type) were transformed into numeric formats.
# Feature Engineering
Key features were derived to enhance analysis:

Sentiment Analysis: VADER classified reviews as positive, neutral, or negative.
Aspect-Based Sentiment: Scores for specific aspects (e.g., food, comfort) were calculated.
Aggregated Ratings: Combined scores reflected overall satisfaction.
# Exploratory Data Analysis (EDA)
Visualizations revealed sentiment distributions, correlations, and ratings across key flight aspects like food and seat comfort. Insights from EDA guided feature selection for clustering.
# Clustering
Process
Preparation: Data was standardized and reduced using PCA.
Algorithms: K-Means, DBSCAN, and agglomerative clustering were applied.
Evaluation: Silhouette scores determined the best clustering method.
Results
K-Means achieved the highest silhouette score, identifying four passenger segments.
# Cluster Insights
1. Elite Flyers
Profile: Highly satisfied with all aspects.
Action: Strengthen loyalty programs and premium services.
2. Content Flyers
Profile: Moderately satisfied, with minor areas needing improvement.
Action: Enhance food and seat comfort to boost satisfaction.
3. Happy Flyers
Profile: Mixed feedback, with significant dissatisfaction in specific areas.
Action: Address issues in food quality and comfort to retain customers.
4. Frustrated Flyers
Profile: Highly dissatisfied across multiple aspects.
Action: Focus on immediate improvements in seating, food, and service.
