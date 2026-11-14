# CS508 — Elective I: Natural Language Processing — PLAN

**Semester:** 5 · **Credits:** 3 · **Level:** Advanced
**Theory:** 45 hrs · **Lab:** 15 hrs · **Tools:** Python, NLTK, spaCy, Hugging Face Transformers, PyTorch

## Syllabus

### Unit 1 — Text Processing Foundations (9 lectures)
1. What NLP is — tasks, applications, and limits
2. Text normalisation — lowercasing, punctuation, Unicode
3. Tokenisation — word, subword, sentence
4. Stop words — why they matter, why they don't
5. Stemming — Porter and Snowball
6. Lemmatisation with spaCy
7. Part-of-speech tagging
8. Named entity recognition
9. Dependency parsing

### Unit 2 — Classical NLP Representations (9 lectures)
1. Bag of words
2. TF-IDF
3. n-gram language models
4. Word embeddings — Word2Vec and GloVe
5. Embedding arithmetic and semantic analogies
6. Document similarity — cosine similarity
7. Text classification with classical ML
8. Topic modelling — LDA
9. Sentiment analysis with a lexicon

### Unit 3 — Neural NLP (9 lectures)
1. Feed-forward networks for text
2. Recurrent neural networks (RNNs) for sequence data
3. LSTM and GRU
4. Sequence-to-sequence models
5. Attention mechanism — from RNN to Transformer
6. The Transformer architecture — encoders, decoders, self-attention
7. BERT — bidirectional pre-training
8. GPT — autoregressive generation
9. Fine-tuning pre-trained models

### Unit 4 — Modern Applications (9 lectures)
1. Text classification with transformers
2. Named entity recognition with transformers
3. Question answering systems
4. Machine translation — encoder-decoder models
5. Text summarisation — extractive vs abstractive
6. Text generation — prompting and sampling strategies
7. Semantic search and embeddings-based retrieval
8. Retrieval-augmented generation (RAG)
9. Chatbots and dialogue systems

### Unit 5 — Evaluation and Ethics (9 lectures)
1. Evaluation metrics — precision, recall, F1, BLEU, ROUGE
2. Human evaluation — when metrics fail
3. Bias in NLP models — sources and detection
4. Toxicity detection and filtering
5. Privacy — PII detection and redaction
6. Hallucination in LLMs — causes and mitigations
7. Multilingual NLP — low-resource languages
8. Responsible deployment — guardrails and monitoring
9. Future directions — multimodal models, reasoning

## Practical Labs (15)

1. Text normalisation and tokenisation with NLTK
2. spaCy — lemmatisation, POS tagging, NER on real text
3. Bag of words and TF-IDF — implement from scratch
4. Word2Vec — train embeddings on a small corpus
5. Document similarity — find near-duplicate documents
6. Text classification with scikit-learn (SMS spam dataset)
7. Topic modelling with LDA on news articles
8. RNN-based text classifier from scratch in PyTorch
9. Train an LSTM language model
10. Attention visualisation in a sequence-to-sequence model
11. Fine-tune BERT for sentiment classification
12. Named entity recognition with a fine-tuned transformer
13. Text summarisation with Hugging Face `summarization` pipeline
14. Semantic search — embed documents and query with embeddings
15. Final project — a working NLP application with evaluation report

## Assignments

1. Text preprocessing pipeline writeup
2. Classical vs neural — text classification comparison
3. Attention and transformer — conceptual writeup with a small implementation
4. Fine-tuning report — hyperparameters, results, failures
5. Final project — end-to-end NLP application with ethical considerations
