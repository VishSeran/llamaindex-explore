# LlamaIndex Explore

LlamaIndex Explore is a learning and experimentation repository focused on advanced retrieval techniques available in LlamaIndex.

The goal of this project is to understand how different retrievers work, compare their performance, and learn when to use each retrieval strategy in Retrieval-Augmented Generation (RAG) applications.

---

## Objectives

- Learn the fundamentals of LlamaIndex retrieval pipelines.
- Implement and test multiple retriever types.
- Compare retrieval quality and performance.
- Explore hybrid retrieval approaches.
- Build a strong understanding of modern RAG architectures.

---

## Retrievers Covered

### 1. Vector Index Retriever

Retrieves documents based on semantic similarity using embeddings.

**Concepts**
- Vector embeddings
- Similarity search
- Top-K retrieval
- Semantic matching

**Use Cases**
- Question answering
- Knowledge bases
- Semantic search systems

---

### 2. BM25 Retriever

Traditional keyword-based retrieval using the BM25 ranking algorithm.

**Concepts**
- Keyword matching
- TF-IDF principles
- Lexical search

**Use Cases**
- Exact term matching
- Search engines
- Hybrid search systems

---

### 3. Document Summary Retriever

Retrieves documents using generated summaries instead of full document content.

**Concepts**
- Document summarization
- Summary indexing
- Context reduction

**Use Cases**
- Large documents
- Long reports
- Efficient retrieval

---

### 4. Auto Merging Retriever

Retrieves fine-grained chunks and automatically merges related parent nodes.

**Concepts**
- Hierarchical chunking
- Parent-child relationships
- Context reconstruction

**Use Cases**
- Large document collections
- Improved context retrieval
- Better answer generation

---

### 5. Recursive Retriever

Performs multi-level retrieval by traversing relationships between nodes.

**Concepts**
- Recursive search
- Graph-based retrieval
- Linked document exploration

**Use Cases**
- Knowledge graphs
- Complex document structures
- Multi-hop reasoning

---

### 6. Query Fusion Retriever

Combines results from multiple query variations to improve retrieval quality.

**Concepts**
- Query expansion
- Multi-query retrieval
- Result fusion
- Reciprocal Rank Fusion (RRF)

**Use Cases**
- Ambiguous questions
- Improved recall
- Advanced RAG systems

---

## Project Structure

```text
llamaindex-explore/
│
├── data/
│   ├── sample_docs/
│   └── datasets/
│
├── notebooks/
│   ├── vector_index_retriever.ipynb
│   ├── bm25_retriever.ipynb
│   ├── document_summary_retriever.ipynb
│   ├── auto_merging_retriever.ipynb
│   ├── recursive_retriever.ipynb
│   └── query_fusion_retriever.ipynb
│
├── src/
│   ├── vector_index/
│   ├── bm25/
│   ├── document_summary/
│   ├── auto_merging/
│   ├── recursive/
│   └── query_fusion/
│
├── requirements.txt
├── README.md
└── .gitignore
