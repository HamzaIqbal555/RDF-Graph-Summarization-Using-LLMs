# RDF-Graph-Summarization-Using-LLMs

We have worked on RDF Knowledge Graph Summarization and Entity Distinguishability task using LLMs.

## Project Overview
- We use structured data from DBpedia
- Apply frequency analysis, property filtering, and prompt-based summarization
- Generate clear summaries of multiple entities

## Model Evaluation
We tested three powerful LLMs:
1. ChatGPT
2. DeepSeek
3. Mistral

All three models were used to generate summaries and distinguish entity characteristics using structured prompts.

## Evaluation Results

### Human Evaluation:
- **DeepSeek** performed best in clarity, structure, and informativeness
- **Mistral** came second
- **ChatGPT** ranked lowest in human preference

### Automated Metrics:
- **ChatGPT** had the best Entity Retention and highest Readability Score
- All models achieved a Grammar Score around 99%

## Conclusion
Our results demonstrate that LLMs can generate reasonable and useful summaries when given clean, preprocessed RDF data.
