### Hi, I'm Agampal

Master of Computer Science (Data Science and AI) student at the University of Sydney. At Sun Life Global Solutions I built an organisation-wide RAG assistant on Amazon Bedrock that answered questions over company documents and codebases.

I work on retrieval, evaluation and the systems underneath them, and I measure things before I claim them.

**Looking for:** software engineering and ML internships and graduate roles in Sydney or India.

#### Projects

| Project | What it is |
| --- | --- |
| [automl-research-harness](https://github.com/Agampal007/automl-research-harness) | An unattended loop in which an LLM proposes and runs ML experiments, with guarded execution and noise-aware acceptance. With a local 27B model as researcher it cut error on Forest Covertype from 8.6% to 3.4% in 26 iterations, confirmed on a test split the model never saw. |
| [vectordb](https://github.com/Agampal007/vectordb) | A vector database written from scratch in Java. On SIFT-1M (1M vectors) the HNSW index reaches recall@10 of 0.975 at 169x the speed of exact search. Writes go through a checksummed write-ahead log with snapshots, and a test kills the writer process 16 times without losing an acknowledged write. It runs as an HTTP service in Docker, with searches on every core (57,000+ a second on 24 threads over 100k vectors). |
| [rag-retrieval-bench](https://github.com/Agampal007/rag-retrieval-bench) | TF-IDF, BM25, LSA, MiniLM and fusion compared on 10,570 SQuAD questions. With the weight chosen on held-out articles, BM25 + MiniLM fusion lifted MRR@10 from 0.815 to 0.857. |
| [llm-eval-harness](https://github.com/Agampal007/llm-eval-harness) | Evaluation for RAG systems with bootstrap confidence intervals and a CI regression gate. On SQuAD v2.0, an LLM reader raised unanswerable-question detection from 9% to 68%. |
| [forecast-lab](https://github.com/Agampal007/forecast-lab) | Seven forecasting models with rolling-origin backtests and calibrated intervals, served through FastAPI. On four years of real NSW electricity demand, ridge with public-holiday features cut error by 26% against seasonal-naive. |

#### Tools I use

Python · Java · SQL · AWS (Bedrock, OpenSearch) · FastAPI · PyTorch · scikit-learn · Docker · GitHub Actions · React

#### Contact

[LinkedIn](https://linkedin.com/in/agampal-singh-185882259)
