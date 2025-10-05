# Cross-Language-Information-Retrieval-Model

Cross Language Information Retrieval (CLIR)
This project aims to build a cross-language information retrieval system that accepts queries in German and retrieves relevant English documents, while presenting results back in German.

Machine Translation: Developed word-alignment tools and translation probability tables using the Europarl parallel corpus.

Information Retrieval: Implemented a Vector Space Model (VSM) for retrieving relevant English documents based on translated queries.

Evaluation: Performance assessed using standard IR evaluation techniques (precision, recall, MAP) on a separate development dataset.

Datasets Used:

bitext.(en,de) → German-English parallel corpus (Europarl).

newstest.(en,de) → Parallel corpus for translation evaluation.

devel.(docs,queries,qrel) → English Wikipedia documents, German queries, and relevance judgments.

This project demonstrates how machine translation and IR techniques can be combined to overcome language barriers in information retrieval.
