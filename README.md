This project demonstrates the end-to-end process of data extraction, cleaning, sentiment analysis, and interactive data visualization. It showcases key skills for data analysts, including SQL for data cleaning, Python for sentiment analysis, and Power BI for building interactive dashboards. The project focuses on transforming raw marketing data into actionable insights, with the goal of providing businesses with a better understanding of customer feedback and marketing performance.

Project Steps
1. SQL Data Extraction & Cleaning
The first step involves extracting customer reviews data from a SQL database and applying various transformations to clean and prepare the data for analysis. This is done through the following steps:

Connecting to SQL Database: Retrieving the customer reviews data from the SQL database.

Data Cleaning: Removing duplicates, handling missing values, and performing any necessary transformations to ensure the data is accurate and ready for analysis.

3. Sentiment Analysis with Python
In this step, we enhance the marketing data by incorporating sentiment analysis, allowing us to gain deeper insights into customer feedback. We'll use the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from the nltk Python library to analyze the emotions conveyed in the reviews.

Steps include:

Extracting Customer Reviews: Retrieving review data from the SQL database.

Sentiment Scoring: Applying VADER sentiment analysis to calculate sentiment scores for each review.

Classification: Categorizing sentiment scores into practical categories (e.g., Positive, Neutral, Negative).

Data Enrichment: Adding the sentiment analysis results back into the dataset to provide richer insights.

5. Building an Interactive Marketing Analytics Dashboard in Power BI
Finally, we visualize the enriched and cleaned marketing data using Power BI to create an interactive and insightful dashboard. This dashboard allows users to explore key insights about customer sentiments and marketing performance.

Steps include:

Importing Data into Power BI: Connecting SQL to Power BI and loading the cleaned and sentiment-enriched data into Power BI.

Creating Visualizations: Designing various visualizations such as bar charts, pie charts, and sentiment trend graphs to highlight important insights.

Dashboard Design: Creating an interactive dashboard that allows users to filter and explore the data in an intuitive way.
