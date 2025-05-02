# RedSQL Benchmark

**RedSQL** is the first benchmark designed to evaluate the performance of text-to-SQL models in domain-specific settings using the Russian language. It includes realistic databases, SQL queries, and natural language questions across 9 critical domains, such as medicine, aviation, banking, and logistics.

## Repository Structure

- `databases/`  
  Contains SQLite databases for each domain with schemas and populated data used during evaluation.

- `models_responses/`  
  Stores model predictions (SQL queries) generated from different large language models under few-shot prompting in both English and Russian.

- `subsets/`  
  Includes the curated benchmark subsets: text-to-SQL pairs grouped by domain, with Russian questions and gold SQL labels.

## Usage

You can use this benchmark to:
- Evaluate model generalization under domain shift.
- Analyze cross-lingual prompting performance (EN vs RU).
- Benchmark domain robustness of new or fine-tuned LLMs on structured tasks.
