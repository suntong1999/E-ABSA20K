# E-ABSA20K: A Dataset and Propose-and-Verify Framework for Aspect-Based Sentiment Analysis in Long E-commerce Reviews

Official repository for the paper:

**E-ABSA20K: A Dataset and Propose-and-Verify for Aspect-Based Sentiment Analysis in Long E-commerce Reviews**

This repository provides the **E-ABSA20K dataset**, **annotation guidelines**, **aspect inventories**, and related resources for **review-level aspect-based sentiment analysis (ABSA)** in long, real-world e-commerce reviews.

---

## Overview

Aspect-Based Sentiment Analysis (ABSA) aims to extract structured sentiment information such as targets, aspects, opinions, and sentiments from text. While many public ABSA benchmarks focus on short texts and limited domains, real e-commerce reviews are often:

- longer and more discourse-rich,
- more aspect-dense,
- more colloquial and noisy,
- and more likely to contain cross-sentence evidence, comparisons, conditionals, and scope ambiguity.

To support research in this setting, we introduce **E-ABSA20K**, a multi-domain review-level ABSA dataset with **20,000 e-commerce reviews** from four product categories:

- **WomenBags**
- **Dresses**
- **Cosmetics**
- **Furniture**

Each review is annotated with **sentiment quads**:

```text
(target, aspect, opinion, sentiment)
