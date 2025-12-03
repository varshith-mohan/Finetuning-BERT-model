# Finetuning-BERT-model
BERT uses a Transformer-based encoder only architecture, and is pre-trained on large unlabeled text corpora using masked language modeling (MLM) and next-sentence prediction (NSP)

- It produces contextualized embeddings: each word’s representation depends on its surrounding context (left and right), unlike older static embedding methods (eg word2vec / GloVe)

- BERT is mainly used for language understanding (NLU) — not text generation. It helps assistants understand what the user means, not what to reply.

- BERT sometimes underperforms for very short texts or tasks with limited data; so many works focus on combining BERT with other architectures for better performance.

- BERT / DistilBERT	used for NER, classification, embeddings	- Small, fast, cheap inference

- RoBERTa / DeBERTa	used for Classification, QA, summarization - High accuracy, Kaggle/enterprise use

- MPNet / MiniLM	used for  Vector search, semantic retrieval (RAG)	Best for FAISS/Pinecone retrieval

- T5 / Flan-T5	used for  Summarization, translation, instruction tasks	 - Lightweight text-to-text generation

- BART / Pegasus	used for  Abstractive summarization	- Less resource-hungry than LLMs

- XLNet / Electra	used for Classification, QA (legacy setups)	- Still optimized for speed

- XLM-R / mT5 / LaBSE	used for  Multilingual NLP, translation, cross-lingual search	- 100+ language support, enterprise use
