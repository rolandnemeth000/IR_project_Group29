# Setup and Installation
Welcome to the GitHub repository for the Information Retrieval Project by Group-T-29 (Alexandru Ciutacu - s1032974, Roland Németh s1033711)! Our project is focused on developing and evaluating information retrieval strategies, namely query expansion, and then compare it to normal BM25. We're utilizing Python libraries to handle and analyze the CORD-19 dataset for COVID-19 related research.
# Data and Experiments
We are using the CORD-19 dataset, specifically the Round 5 subset, to evaluate our information retrieval strategies. We do the following:

    Baseline BM25 ranking
    Query expansion using synonyms with different thresholds
    Weighted query expansion with different thresholds

The results are presented in multiple JSON files and visualized using plots and a table.

## Note 1
Please note that intermediary files generated during the experiments are too big to include in the repository.

## Note 2
You need roughly 16 GB of free RAM due to the extensive data processing involved.

## Note 3
It is a self-contained file, every result and experiment can be replicated by running the notebook.


# Conclusion
Contrary to expectations, our results indicated that these strategies reduced the effectiveness of information retrieval compared to the baseline. This suggests that the unique nature of medical literature necessitates more contextually nuanced approaches. The findings highlight the complexities of query expansion in the medical domain and point towards the need for more specialized techniques in information retrieval.
