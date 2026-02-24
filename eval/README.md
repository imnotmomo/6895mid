# Evaluation files

This folder contains starter evaluation sets for the midterm checkpoint.

- rag_eval_set.json
  - For each query, check whether at least one of the top-k retrieved chunks comes from an expected source.
  - Report Hit@k and MRR.

- llm_eval_set.json
  - Prompts for end-to-end advisor behavior checks.
  - Score: refusal correctness, citation presence, and "zero critical errors".
