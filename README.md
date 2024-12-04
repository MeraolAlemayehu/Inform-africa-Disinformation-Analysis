## How the Python Code Supports the Framework: User Guide

The Python code is designed to assist users in analyzing disinformation data collected through the custom portal. After downloading the data in CSV or JSON format, the Python script can be executed to process, analyze, and visualize the data effectively, supporting the goals of the DISARM framework. Here's how the code works step-by-step:

### 1. **Data Preparation**
   - **Import the Data**: Start by importing the CSV or JSON file into the Python environment. The code reads the file and converts the data into a format that can be easily processed.
   - **Preprocessing**: The script performs initial cleaning tasks such as removing duplicates, filling in missing values, and standardizing date formats to ensure that the data is consistent and ready for analysis.

### 2. **Sentiment Analysis**
   - **Analyzing Post Sentiment**: The Python code uses natural language processing (NLP) libraries to analyze the sentiment of each post in the dataset. It detects whether the post is positive, negative, or neutral, helping to understand the emotional tone of the disinformation.
   - **Sentiment Visualization**: After the sentiment is determined, the code generates visualizations (like bar graphs or pie charts) to show the distribution of sentiments across all posts.

### 3. **Text Analysis and Topic Modeling**
   - **Word Frequency**: The code analyzes the most frequently used words or phrases in the posts. By identifying common terms, the code helps uncover recurring themes or topics that could indicate the primary focus of disinformation.
   - **Topic Modeling**: The script groups similar words and phrases into broader topics, allowing users to quickly identify the main narrative driving the disinformation campaign. This step aids in categorizing the posts by their key themes.

### 4. **Detection of Manipulative Language**
   - **Identifying Emotional or Manipulative Terms**: The Python code is equipped with algorithms that detect manipulative language, such as exaggerated claims, fear-mongering, or emotionally charged words. These are often used in disinformation campaigns to sway public opinion.
   - **Highlighting Risky Posts**: Posts that contain manipulative language are flagged, making it easier for the user to focus on the most harmful or misleading content.

### 5. **Data Visualization**
   - **Visual Representation of Data**: The script generates various types of visualizations to aid in understanding the data, such as:
     - **Word Clouds**: To display the most common terms used in disinformation posts.
     - **Bar Graphs and Pie Charts**: These are used to show the distribution of post types, sentiment analysis results, and the prevalence of different disinformation strategies.
   - **Easy Interpretation**: The visualizations help users quickly identify patterns, trends, and outliers in the data.

### 6. **Statistical Analysis**
   - **Generating Reports**: The Python code runs statistical analysis to produce detailed reports summarizing the results of the sentiment analysis, topic modeling, and other key metrics. These reports provide insights into the scale and nature of the disinformation campaigns.
   - **Impact Assessment**: By analyzing the data, users can assess the impact of disinformation and evaluate which strategies are being most effectively used.

### 7. **Exporting Results**
   - **Download Processed Data**: Once the analysis is complete, the code allows users to download the results, including visualizations and reports, in various formats (e.g., CSV, JSON, or image files). This makes it easy for users to share the findings or further analyze the data with other tools.

By following this user guide and running the Python code on your downloaded data, you can efficiently analyze disinformation content and gain valuable insights that align with the goals of the DISARM framework. The code automates many complex tasks, ensuring that even large datasets can be handled with ease.
