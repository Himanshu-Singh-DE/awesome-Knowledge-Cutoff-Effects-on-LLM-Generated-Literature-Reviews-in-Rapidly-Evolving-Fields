# GitHub Implementations

This section contains open-source GitHub implementations and research repositories related to **knowledge cutoffs, temporal knowledge, retrieval-augmented generation (RAG), and freshness-aware LLM evaluation**.

## 1. Self-RAG

**Repository:** https://github.com/AkariAsai/self-rag

**Research:** *Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection*

**Authors:** Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi

**Year:** 2024

**Purpose:**
Self-RAG is an implementation of a retrieval-augmented language model that learns when to retrieve external information and how to critique its own generated responses. The repository provides code, models, training data, retrieval components, and evaluation scripts.

**Why it is relevant:**
It is directly relevant to this topic because external retrieval can help language models overcome limitations caused by static or outdated parametric knowledge.

**License / Reproducibility:**
The repository provides installation instructions, requirements, training procedures, retrieval setup, inference scripts, and evaluation procedures.

---

## 2. Dated Data

**Repository:** https://github.com/nexync/dated_data

**Research:** *Dated Data: Tracing Knowledge Cutoffs in Large Language Models*

**Authors:** Jeffrey Cheng, Marc Marone, Orion Weller, Dawn Lawrie, Daniel Khashabi, Benjamin Van Durme

**Year:** 2024

**Purpose:**
Dated Data investigates how to identify the effective temporal boundary of knowledge encoded in large language models.

**Why it is relevant:**
This is one of the most directly relevant implementations for the research topic because it focuses specifically on measuring and understanding knowledge cutoffs in LLMs.

**Evaluation focus:**
The project can be used to study whether models actually possess knowledge about information from particular points in time.

**Repository:**
https://github.com/nexync/dated_data

---

## 3. AutoSurvey

**Repository:** https://github.com/AutoSurveys/AutoSurvey

**Research:** *AutoSurvey: Large Language Models Can Automatically Write Surveys*

**Year:** 2024

**Purpose:**
AutoSurvey investigates the automatic generation of literature surveys using large language models. The approach decomposes survey generation into multiple stages including retrieval, outlining, drafting, integration, refinement, and evaluation.

**Why it is relevant:**
This implementation is particularly relevant because the main assignment topic concerns **LLM-generated literature reviews**. It provides a practical example of using LLMs to automate parts of the literature-review process.

**Research application:**
The repository can be used as a starting point for studying automated survey generation, retrieval quality, organization of research findings, and evaluation of generated literature reviews.

**Repository:**
https://github.com/AutoSurveys/AutoSurvey

---

## 4. Time-Sensitive QA

**Repository:** https://github.com/wenhuchen/Time-Sensitive-QA

**Research:** *A Dataset for Answering Time-Sensitive Questions*

**Authors:** Wenhu Chen, Xinyi Wang, William Yang Wang

**Year:** 2021

**Purpose:**
This repository provides resources for evaluating question answering when the correct answer depends on information that can change over time.

**Why it is relevant:**
A literature-review system must be able to distinguish older information from newer information. Time-sensitive question answering provides a useful evaluation setting for testing whether an LLM understands temporal changes.

**Research application:**
The dataset and associated code can be useful for testing temporal reasoning and identifying cases where an LLM relies on outdated information.

**Repository:**
https://github.com/wenhuchen/Time-Sensitive-QA

---

## 5. FreshBench

**Repository:** https://github.com/FreedomIntelligence/FreshBench

**Research area:** Freshness and temporal generalization of LLMs

**Purpose:**
FreshBench provides resources for evaluating how well language models handle information that changes over time. The repository contains evaluation-related code, data, scripts, and RAG components.

**Why it is relevant:**
Freshness is a central problem in knowledge-cutoff research. A model can produce a fluent answer while relying on information that is no longer current. Freshness-oriented benchmarks help evaluate this problem systematically.

**Repository activity:**
The GitHub repository contains multiple directories and more than 20 commits, including components for retrieval-augmented generation, testing, scripts, and answer data.

**Repository:**
https://github.com/FreedomIntelligence/FreshBench

---

## Comparison of Implementations

| Implementation        | Main Focus                      | Relevance to Topic                                   |
| --------------------- | ------------------------------- | ---------------------------------------------------- |
| **Self-RAG**          | Retrieval + self-reflection     | Helps reduce dependence on static model knowledge    |
| **Dated Data**        | Knowledge cutoffs               | Directly studies effective knowledge boundaries      |
| **AutoSurvey**        | Automated literature surveys    | Directly related to LLM-generated literature reviews |
| **Time-Sensitive QA** | Temporal question answering     | Evaluates knowledge that changes over time           |
| **FreshBench**        | Freshness / temporal evaluation | Evaluates whether models handle current information  |

## Overall Relevance

These repositories collectively cover the major technical components of the research problem:

1. **Knowledge cutoff measurement** — Dated Data
2. **External knowledge retrieval** — Self-RAG
3. **Automated literature review generation** — AutoSurvey
4. **Temporal reasoning** — Time-Sensitive QA
5. **Freshness evaluation** — FreshBench

Together, they provide a useful starting point for reproducing experiments and developing systems that generate more current, evidence-supported literature reviews.

