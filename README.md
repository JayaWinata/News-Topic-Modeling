# Topic Classification and Modeling Using API-Sourced News Data
This project aims to classify and analyze news articles by topic, leveraging data fetched through the SerpAPI. The workflow involves retrieving topic-specific news, preprocessing the text, and applying machine learning models such as Latent Dirichlet Allocation (LDA) or Non-Negative Matrix Factorization (NMF) for topic modeling. Additionally, classification metrics are evaluated to measure the model's performance.
## Key Steps
1. Data Acquisition:

- Fetch news data from the SerpAPI using predefined topic tokens (e.g., "technology," "sports," "entertainment").
- Extract relevant text data from JSON responses.
2. Preprocessing:

- Tokenize and clean the data.
- Apply transformations like TF-IDF vectorization to prepare text for modeling.
3. Topic Modeling:

- Use algorithms such as LDA and NMF to identify latent topics within the dataset.
4. Classification:

- Split the data into training and testing sets.
- Train models and evaluate their performance using metrics like accuracy, confusion matrix, and classification reports.
5. Visualization:

- Plot results to illustrate the most relevant words for each topic.
## Project Limitations
1. API Dependency:

- Reliance on SerpAPI limits the project to the availability and structure of the API. Downtime or changes in API structure could disrupt the workflow.
2. Data Diversity:

- News data may not represent the full range of topics due to predefined tokens and specific API parameters.
3. Model Scalability:

- LDA and NMF performance may degrade with very large datasets or high-dimensional feature spaces.
4. Evaluation Constraints:

- Without a large labeled dataset, evaluation of topic coherence and classification accuracy may be limited.
