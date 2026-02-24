# Modern NLP & Attention Architectures

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Integrated-ee4c2c)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![NLP](https://img.shields.io/badge/Domain-NLP-orange)
![License](https://img.shields.io/badge/Code_License-MIT-green)

A structured collection of Natural Language Processing implementations. This repository bridges the gap between classical linguistic processing and modern deep learning, showcasing the evolution from N-gram models to Attention-based Neural Machine Translation and Transformer fine-tuning.

## 📌 Repository Structure

The projects are logically grouped into four primary domains:

### 1. 🧠 BERT Sentiment Analysis
Focuses on adapting pre-trained Large Language Models for downstream classification tasks.
* **Implementation:** Fine-tuning the `bert-base-uncased` Transformer model on the IMDb dataset for binary sentiment classification, utilizing the Hugging Face `transformers` library.

### 2. 🌍 Neural Machine Translation (Seq2Seq)
Explores the architecture that revolutionized machine translation before the dominance of decoders.
* **Models:** * Implementation of a standard Seq2Seq Encoder-Decoder model.
  * Implementation of an Attention-based model with programmatic extraction and visualization of attention weights over input tokens.

### 3. ⚙️ Prompt Engineering & Evaluation
A quantitative look at how context injection affects model performance.
* **Implementation:** Simulation and comparative evaluation of Zero-shot vs. Few-shot prompting strategies, specifically measuring translation accuracy and inference latency.

### 4. 🔤 Text Processing Fundamentals
Covers the foundational algorithms required for lexical and syntactic analysis.
* **Implementations:** * Tokenization, Part-of-Speech (POS) tagging, and Context-Free Grammar (CFG) parsing.
  * Computation of BLEU and Perplexity scores to evaluate N-gram and Recurrent Neural Network (RNN) language models.

## 🚀 Getting Started

**1. Clone the repository:**
```bash
git clone [https://github.com/yourusername/Modern-NLP-Architectures.git](https://github.com/yourusername/Modern-NLP-Architectures.git)
cd Modern-NLP-Architectures
