# Goodreads Book Analysis and Rating Prediction

# Project Overview
This project focuses on analyzing Goodreads book data to uncover patterns and trends in book ratings. Additionally, the project aims to predict book ratings based on various features such as title, author, and other metadata. The project leverages Python libraries for data manipulation, visualization, and machine learning.

Data Sources
- Goodreads Dataset: This dataset contains information about books, including their titles, authors, and user ratings. It was read from a CSV file, and some preprocessing was required to handle missing or misaligned rows.
- ISBN Metadata: Additional metadata extracted from ISBN numbers was included, although some columns were later dropped due to redundancy with the Goodreads dataset. (isbn_metadata_code.ipynb)

Key Libraries and Tools
- Pandas: For data manipulation and cleaning.
- Matplotlib & Seaborn: For data visualization.
- Plotly: For interactive visualizations.
- Scikit-learn: For machine learning, including feature extraction and encoding.

Project Structure
1. Data Cleaning and Preparation  
  - Misaligned or incomplete rows in the dataset were identified and dropped.
  - The isbn and isbn13 columns were dropped after determining that their information was redundant with other available data.
2. Exploratory Data Analysis
  - Basic statistical analysis was performed to understand the distribution of ratings.
  - Special attention was given to books with low ratings to identify any patterns.
3. Feature Engineering
  - The book titles were cleaned to extract the main title, removing any extraneous information such as subtitles or series information.
4. Modeling
  - Various machine learning models may have been applied (further details needed upon full review of the notebook).

Results and Findings
The analysis revealed that the majority of average ratings are clustered between 3.78 and 4.14
Both Gradient Boosting and Random Forest are viable options to predict Book Ratings from the provided attributes

How to Run the Project
1. Clone this repository.
2. Ensure all necessary libraries are installed. You can install them using:
   bash
   Copy the code
   pip install -r requirements.txt
3. Download the datasets and place them in the appropriate directory
4. Before running the code, be sure to have updated the two file paths at the start of the code
5. Run the Jupyter Notebook to explore the data and execute the analysis.

# Authors
Lucy AKITT
Hasina Angelina RAJOELIMBOLOLONA
Lorenzo IERFINO
