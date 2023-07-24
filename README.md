**Exploratory Data Analysis**

**Task Summary:**
In this project, we performed an Exploratory Data Analysis (EDA) on multiple datasets. The [datasets](https://www.kaggle.com/datasets/tariqmassaoudi/hespress) include information from Hespress stories such as 'id', 'title', 'date', 'author', 'story', and 'topic'. The goal of the analysis was to gain insights into the combined dataset and distributions present in the data.

**Steps Followed:**
1. **Data Merging:**
We began by merging all the individual datasets into one combined CSV file. This step was performed using Python and the Pandas library, ensuring easy access and analysis of the entire dataset.

2. **Data Exploration:**
With the combined dataset in place, we proceeded to explore its structure, basic statistics, and identify any missing values.

3. **Number of Examples per Class (Topic):**
One of the first insights we derived was the distribution of examples across different topics. We used visualization (bar plot) to showcase the number of examples per topic, giving us an understanding of the dataset's topic distribution.

4. **Top Frequent N-grams:**
We analyzed the most frequent n-grams (word sequences) present in the 'story' column. The goal was to gain insights into the most commonly occurring word combinations, which could help us identify recurrent themes or keywords.

5. **Lengths of Examples in Words and Letters:**
To understand the length of articles in the dataset, we calculated the number of words and letters in each example. Visualization (histograms) helped us visualize the distribution of article lengths.

**Results:**
- The distribution of examples per topic revealed the prevalence of certain topics over others, providing valuable information about the dataset's content focus.
- The analysis of top frequent n-grams shed light on recurrent word combinations, indicating potential significant phrases and language patterns within the articles.
- The examination of article lengths in words and letters allowed us to understand the typical article size in the dataset and identify any potential outliers.

**Next Steps:**
Based on the insights gained from this EDA, further analysis or machine learning tasks can be planned. Depending on the project's objectives, natural language processing (NLP) techniques or topic modeling can be applied to gain deeper insights into the content of the articles.

