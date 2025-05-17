# KG2RAG

First KG-Integrated RAG Framework: KG2RAG is the first framework to deeply integrate KGs into the RAG pipeline, combining semantic retrieval with graph-based expansion and organization.

Novel Techniques:
* ﻿Graph-Guided Chunk Expansion: Leverages KG entity relationships to retrieve contextually relevant but semantically diverse chunks.
* ﻿KG-Driven Context Structuring: Filters and ranks retrieved chunks using KG-based metrics (e.g., cross-encoder reranking).

Robust Evaluation: Introduces Shuffle-HotpotQA, a variant of HotpotQ with entity replacement, to validate robustness against prior knowledge bias.
