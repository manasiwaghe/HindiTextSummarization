# Evaluation Results
Final aggregated results for all methods:
[Google Sheets – Full Evaluation](https://docs.google.com/spreadsheets/d/1ZIRhJW8KPh-tGnp0RSIWvk_R1RrmD5Tb3QvwG1okj6Q/edit?usp=sharing)

# Summary of Findings
-Traditional methods (token-based), particularly with cosine similarity, achieved the highest overall ROUGE scores.
This can be attributed to their focus on exact word overlap, which aligns with the ROUGE evaluation methodology.

-WordNet-based semantic similarity recorded the highest ROUGE-2 scores.
By incorporating synonym-level information, it captured semantically meaningful bigrams, enhancing bigram overlap evaluation.

-FastText-based methods consistently underperformed relative to other approaches.
Although these methods encode semantic relationships via embeddings, ROUGE does not reward semantic similarity unless lexical matches are present.

