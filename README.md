# SciFact Information Retrieval Experiments

I used this coursework repository to explore how scientific documents can be ranked against claims in the SciFact dataset. It contains text preprocessing, indexing, lexical ranking, and model-based retrieval experiments.

## What it includes

- Parse the SciFact corpus and queries into a shared representation.
- Normalize text, remove stopwords, and apply Porter stemming.
- Build an inverted index and reuse cached preprocessing.
- Implement a BM25 ranking baseline.
- Integrate BEIR retrieval adapters, including a Sentence-BERT retrieval path.
- Include an optional cross-encoder reranking path.
- Save query-to-document rankings for analysis.

## Project context

The current main script selects a Sentence-BERT model. Other retrieval approaches are represented in the source as experimental alternatives; their presence is not a claim that every configuration has been validated.

The repository includes the dataset files, assignment material, and a [project report](Report.pdf). A separate [TF–IDF coursework repository](https://github.com/Omar-Khattab-01/Vector_Space_Model_Based_Information_Retrieval_System_for_the_SciFact_Dataset) documents the classic vector-space implementation and its team contributions.
