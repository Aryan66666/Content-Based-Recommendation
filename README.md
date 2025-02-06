Project Brief: Product Recommendation System via Web Scraping and Similarity Matching

This project implements a web scraping solution to collect product data from various categories on Flipkart.
The data collected includes product names, ratings, and other relevant details, which are then stored in a CSV file.
After the data is scraped, the system performs essential data cleaning, including replacing missing values, followed by a visualization step to generate a word cloud.
Once cleaned, the data undergoes further processing with the addition of a new column (processed_text). 
The product descriptions are tokenized and vectorized, and cosine similarity is calculated between the products.
The system then employs live web tracking to identify the product the user is currently browsing.
Based on the product name, the system recommends similar products from the dataset using the calculated similarity scores, with recommendations filtered according to a predefined similarity threshold.

Limitations:
Limited Dataset for Recommendations: The system can only recommend products based on a predefined set of products within the dataset.
Similarity Threshold Sensitivity: A suitable similarity threshold is crucial to ensure recommendations are relevant across different product categories.
Web Tracking Scope: The current web tracking functionality supports a single tab or window, limiting its ability to track multiple tabs or windows.
Future Work:
Automation: Automate the data collection process so that the system scrapes products daily at a specified time.
Enhanced Recommendation Techniques: Implement collaborative filtering to incorporate user behavior and enhance the recommendation process, making it more personalized.
