# Week 1: LLM Fundamentals - Data & Tokenization

## 🎯 Overview

Week 1 covers the foundational concepts needed to understand how LLMs work under the hood:
1. **Data Pipeline** - How training data is collected, extracted, and cleaned
2. **Tokenization** - How text is converted to tokens that models can process

---

## 📓 Notebooks

### **1. Data Cleaning Pipeline**
[Open in Colab](https://colab.research.google.com/github/happyahluwalia/llm_journey/blob/main/week-01-data-pipeline/Data_Cleaning_Pipeline.ipynb)

**What you'll build:**
- Data collection from Wikipedia, GitHub, StackExchange
- HTML extraction using Trafilatura
- Multi-stage cleaning pipeline (normalization, language detection, quality filtering)

**Key concepts:**
- Extraction vs. Cleaning
- Quality filtering heuristics
- Deduplication strategies (exact and fuzzy)
- How production datasets (Dolma, FineWeb) approach data cleaning

**Time:** 2-3 hours | **Difficulty:** Beginner-Intermediate

---

### **2. Tokenization Fundamentals**
[Open in Colab](https://colab.research.google.com/github/happyahluwalia/llm_journey/blob/main/week-01-data-pipeline/Tokenization.ipynb)

**What you'll learn:**
- Why tokenization exists (word vs character vs subword)
- How BPE (Byte-Pair Encoding) algorithm works
- Practical token management (counting, costs, context windows)
- Why LLMs struggle with certain tasks (like counting letters in "strawberry")

**Key concepts:**
- BPE algorithm with hands-on example
- Token counting with tiktoken
- Cost optimization strategies
- Context window management

**Time:** 2-3 hours | **Difficulty:** Beginner-Intermediate

---

## 🎓 Learning Outcomes

After completing Week 1, you'll be able to:
- ✅ Understand how production LLMs prepare training data
- ✅ Build a data cleaning pipeline from scratch
- ✅ Explain how tokenization works and why it matters
- ✅ Count tokens and estimate API costs
- ✅ Manage context windows in chatbot applications
- ✅ Optimize prompts for token efficiency


---

## 📚 Resources

**Data Pipeline:**
- [Dolma Dataset](https://huggingface.co/datasets/allenai/dolma)
- [FineWeb Dataset](https://huggingface.co/datasets/HuggingFaceFW/fineweb)
- [Trafilatura Documentation](https://trafilatura.readthedocs.io/)

**Tokenization:**
- [OpenAI Tokenizer Tool](https://platform.openai.com/tokenizer)
- [tiktoken Library](https://github.com/openai/tiktoken)
- [BPE Paper](https://arxiv.org/abs/1508.07909)

---

**Questions or feedback?** Open an issue or contribute!
