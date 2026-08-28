# Verified Scholarly References

> **Verification note:** The references below were selected for their relevance to knowledge cutoffs, temporal knowledge, retrieval-augmented generation, citation reliability, hallucination, and automated literature reviews. Links point to scholarly or official records.

## 1. Survey and Review Papers

### 1. The Life Cycle of Knowledge in Big Language Models: A Survey

**Authors:** Boxi Cao, Hongyu Lin, Xianpei Han, Le Sun
**Year:** 2024
**Venue:** *Machine Intelligence Research*
**Link:** https://doi.org/10.1007/s11633-023-1416-x

**Relevance:** Provides a broad survey of how knowledge is acquired, represented, maintained, updated, and used in large language models.

---

### 2. Static Models, Dynamic World: A Unified Perspective on Temporal Perception in Large Language Models

**Authors:** Chenhao Li, Dandan Song, Changzhi Zhou, Jun Yang, Yuhang Tian, Huipeng Ma, Guangyuan Feng, Luan Zhang, Xudong Li, Ke Duan
**Year:** 2026
**Venue:** *Findings of ACL 2026*
**Link:** https://aclanthology.org/2026.findings-acl.92/

**Relevance:** Studies temporal perception and failure modes that arise when LLMs operate in a constantly changing world.

---

### 3. Knowledge Editing for Large Language Models: A Survey

**Authors:** Song Wang et al.
**Year:** 2024
**Venue:** *ACM Computing Surveys*
**Link:** https://doi.org/10.1145/3698590

**Relevance:** Surveys methods for updating or modifying factual knowledge stored inside pretrained language models.

---

## 2. Foundational Papers

### 4. Language Models as Knowledge Bases?

**Authors:** Fabio Petroni et al.
**Year:** 2019
**Venue:** *EMNLP-IJCNLP 2019*
**Link:** https://aclanthology.org/D19-1250/

**Relevance:** Demonstrates that pretrained language models can encode substantial factual and relational knowledge.

---

### 5. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks

**Authors:** Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela
**Year:** 2020
**Venue:** *NeurIPS 2020*
**Link:** https://arxiv.org/abs/2005.11401

**Relevance:** Introduces Retrieval-Augmented Generation (RAG), combining language-model generation with external retrieved knowledge.

---

### 6. A Dataset for Answering Time-Sensitive Questions

**Authors:** Wenhu Chen, Xinyi Wang, William Yang Wang
**Year:** 2021
**Link:** https://arxiv.org/abs/2108.06314

**Relevance:** Provides a benchmark for answering questions whose answers may change over time.

---

### 7. TruthfulQA: Measuring How Models Mimic Human Falsehoods

**Authors:** Stephanie Lin, Jacob Hilton, Owain Evans
**Year:** 2022
**Venue:** *ACL 2022*
**Link:** https://aclanthology.org/2022.acl-long.229/

**Relevance:** Evaluates whether language models generate truthful answers rather than reproducing common misconceptions.

---

### 8. Probing Across Time: What Does RoBERTa Know and When?

**Authors:** Leo Z. Liu, Yizhong Wang, Jungo Kasai, Hannaneh Hajishirzi, Noah A. Smith
**Year:** 2021
**Venue:** *Findings of EMNLP 2021*
**Link:** https://aclanthology.org/2021.findings-emnlp.71/

**Relevance:** Investigates when different types of information become represented in pretrained language models.

---

## 3. Temporal Knowledge and Knowledge Cutoffs

### 9. Dated Data: Tracing Knowledge Cutoffs in Large Language Models

**Authors:** Jeffrey Cheng, Marc Marone, Orion Weller, Dawn Lawrie, Daniel Khashabi, Benjamin Van Durme
**Year:** 2024
**Link:** https://arxiv.org/abs/2403.12958

**Relevance:** Introduces the concept of an **effective cutoff** and demonstrates that a model's actual knowledge boundary can differ from its reported cutoff.

---

### 10. Is Your LLM Outdated? Evaluating LLMs at Temporal Generalization

**Authors:** Chenghao Zhu, Nuo Chen, Yufei Gao, Yunyi Zhang, Prayag Tiwari, Benyou Wang
**Year:** 2024
**Link:** https://arxiv.org/abs/2405.08460

**Relevance:** Evaluates how LLM performance changes when information becomes temporally distant from the model's training data.

---

### 11. Can Prompts Rewind Time for LLMs? Evaluating the Effectiveness of Prompted Knowledge Cutoffs

**Authors:** Xin Gao, Ruiyi Zhang, Daniel Du, Saurabh Mahindre, Sai Ashish Somayajula, Pengtao Xie
**Year:** 2025
**Venue:** *EMNLP 2025*
**Link:** https://aclanthology.org/2025.emnlp-main.1049/

**Relevance:** Investigates whether prompting can make an LLM behave as if it had an earlier knowledge cutoff.

---

### 12. Tomorrow Brings Greater Knowledge: Large Language Models Join Dynamic Temporal Knowledge Graphs

**Authors:** Christian Di Maio, Andrea Zugarini, Francesco Giannini, Marco Maggini, Stefano Melacci
**Year:** 2025
**Venue:** *Lifelong Learning Agents*
**Link:** https://proceedings.mlr.press/v274/maio25a.html

**Relevance:** Explores connecting LLMs with dynamic temporal knowledge graphs to represent changing information.

---

### 13. RAG or Learning? Understanding the Limits of LLM Adaptation under Continuous Knowledge Drift in the Real World

**Authors:** Hanbing Liu, Lang Cao, Yang Li
**Year:** 2026
**Venue:** *Findings of ACL 2026*
**Link:** https://aclanthology.org/2026.findings-acl.546/

**Relevance:** Studies continuous knowledge drift and evaluates time-aware retrieval as a way to maintain current knowledge.

---

## 4. Citation Reliability, Hallucination and Context

### 14. Evaluating Verifiability in Generative Search Engines

**Authors:** Nelson F. Liu, Tianyi Zhang, Percy Liang
**Year:** 2023
**Venue:** *Findings of EMNLP 2023*
**Link:** https://aclanthology.org/2023.findings-emnlp.467/

**Relevance:** Examines whether citations generated by AI search systems actually support the claims they accompany.

---

### 15. SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models

**Authors:** Potsawee Manakul, Adian Liusie, Mark Gales
**Year:** 2023
**Venue:** *EMNLP 2023*
**Link:** https://aclanthology.org/2023.emnlp-main.557/

**Relevance:** Introduces a method for detecting possible hallucinations by examining consistency between multiple generated responses.

---

### 16. Lost in the Middle: How Language Models Use Long Contexts

**Authors:** Nelson F. Liu et al.
**Year:** 2024
**Venue:** *Transactions of the Association for Computational Linguistics*
**Link:** https://aclanthology.org/2024.tacl-1.9/

**Relevance:** Shows that language models may not use relevant information equally when it is positioned at different locations within long contexts.

---

### 17. FreshLLMs: Refreshing Large Language Models with Search Engine Augmentation

**Authors:** Tu Vu et al.
**Year:** 2024
**Venue:** *Findings of ACL 2024*
**Link:** https://aclanthology.org/2024.findings-acl.813/

**Relevance:** Investigates search augmentation as a method for improving LLM performance on dynamically changing information.

---

## 5. Retrieval-Augmented Generation and Automated Research

### 18. Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection

**Authors:** Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi
**Year:** 2024
**Venue:** *International Conference on Learning Representations (ICLR 2024)*
**Link:** https://openreview.net/forum?id=hSyW5go0v8

**Relevance:** Introduces a self-reflective RAG framework that can retrieve information when needed and critique retrieved evidence and generated responses.

---

### 19. Corrective Retrieval Augmented Generation

**Authors:** Shi-Qi Yan, Jia-Chen Gu, Yun Zhu, Zhen-Hua Ling
**Year:** 2024
**Link:** https://arxiv.org/abs/2401.15884

**Relevance:** Introduces a corrective retrieval mechanism that evaluates retrieved documents and performs corrective actions when retrieval quality is inadequate.

---

### 20. AutoSurvey: Large Language Models Can Automatically Write Surveys

**Authors:** Yidong Wang, Qi Guo, Wenjin Yao, Hongbo Zhang, Xin Zhang, Zhen Wu, Meishan Zhang, Xinyu Dai, Min Zhang, Qingsong Wen, Wei Ye, Shikun Zhang, Yue Zhang
**Year:** 2024
**Venue:** *Advances in Neural Information Processing Systems (NeurIPS 2024)*
**Link:** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d07a9fc7da2e2ec0574c38d5f504d105-Abstract-Conference.html

**Relevance:** Presents a framework for automatically generating literature surveys using retrieval, outlining, drafting, integration, refinement, and evaluation.

---

## Reference Verification Note

The references were selected according to the assignment requirement that scholarly resources should be verified for their title, authors, publication year, venue, identifier/link, existence, and relevance before being added to the repository.

