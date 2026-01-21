# Sentiment-Aware, Serendipity-Oriented Long-Tail Recommender System

This repository accompanies the research work titled:

**“A Sentiment-Aware, Serendipity-Oriented Long-Tail Recommender System”**

The work investigates how integrating **sentiment analysis**, **serendipity-aware ranking**, and **explicit long-tail enforcement** can improve recommendation quality beyond traditional accuracy-focused recommender systems.

---

##  Authors

- **Sahil Burnwal**  
  *First Author*  
  Graduate Researcher  

- **Dr. Richa Singh**  
  *Corresponding Author*  
  Academic Researcher  

---

## Abstract

Modern recommender systems often overemphasize accuracy, resulting in popularity bias and limited exposure to long-tail items. This research proposes a unified recommendation framework that integrates semantic similarity modeling, transformer-based sentiment analysis, unexpectedness-aware utility modeling, and diversity-driven re-ranking. The proposed system improves not only classical relevance metrics but also novelty, serendipity, and long-tail fairness, thereby enhancing user discovery and satisfaction.

---

## Key Contributions

- A **unified sentiment-aware recommendation pipeline**
- Integration of **Unexpectedness-Augmented Utility Model (UAUM)**
- Explicit **long-tail exposure enforcement**
- Comprehensive evaluation using both accuracy and beyond-accuracy metrics
- Benchmarking of multiple transformer-based sentiment models

---

## Methodology Overview

The system combines:
- **Lexical similarity** (TF-IDF)
- **Semantic similarity** (Sentence-BERT / MiniLM)
- **Sentiment-based quality uplift** (DistilBERT)
- **Popularity debiasing**
- **Diversification using xQuAD**
- **Hard tail-ratio constraint** for fairness

This multi-stage pipeline ensures relevance while actively promoting novelty, serendipity, and long-tail content exposure.

---

## Repository Contents

This repository contains:
- Selected notebooks/scripts illustrating core components  
- Benchmarking and evaluation summaries  
- Supporting material related to the research methodology  

> **Note:**  
> Due to data usage restrictions and institutional guidelines, the full dataset and some experimental artifacts are not publicly shared. The repository focuses on reproducibility of the methodology and clarity of the research pipeline.

---

## Data Availability

The primary dataset used in this research (e.g., IMDB movie reviews and metadata) is subject to licensing and usage constraints. As a result:
- Raw datasets are **not included** in this repository
- Processed results and methodological descriptions are provided instead

Researchers interested in replication are encouraged to use publicly available equivalents (e.g., IMDB, MovieLens, Amazon Reviews) following the same preprocessing and modeling steps described in the paper.

---

## Citation

If you use or reference this work, please cite it as:
Sahil Burnwal, Richa Singh.
"A Sentiment-Aware, Serendipity-Oriented Long-Tail Recommender System."

