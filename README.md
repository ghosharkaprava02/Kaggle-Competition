DA5401-2025-Data-Challenge

Arkaprava Ghosh
DA25C003

This repository contains my source code for the DA5401 end-semester data challenge on metric learning applied to conversational AI evaluation.

Overview

The challenge involves building a metric learning model to predict the fitness score (0–10) of a prompt–response pair against a given AI evaluation metric definition embedding. The goal is to accurately model the semantic similarity between the evaluation metric and the test conversation pair.

Data

Metric definition embeddings generated using SentenceTransformer (google/embeddinggemma-300m).

Prompt–response pairs in JSON format.

Ground truth fitness scores from an LLM judge.

Task

Train a model that takes metric definition embeddings and prompt–response pairs as inputs to predict fitness scores with minimal RMSE, enabling automated assessment of conversational AI agents.

Submission

Predictions should be submitted as ID and score pairs in CSV format.
