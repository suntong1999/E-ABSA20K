📄 E-ABSA20K: A Realistic Benchmark for Aspect-Based Sentiment Analysis in E-commerce

Aspect-Based Sentiment Analysis (ABSA) is crucial for extracting actionable product insights from e-commerce reviews. However, most public ABSA benchmarks focus on short texts and limited domains, failing to capture real-world challenges like multi-aspect co-occurrence, colloquial/noisy language, and the need to aggregate evidence across long review contexts.

To address this gap, we introduce E-ABSA20K — a multi-domain dataset of 20,000 real-world reviews from four product categories: Women’s Bags, Dresses, Cosmetics, and Furniture. Each review is annotated with review-level sentiment quads (target, aspect, opinion, sentiment).

🔹 Key features:
Longer & denser: Avg. 63.9 words and 6.0 quads per review — significantly more complex than existing benchmarks.
Realistic noise: Includes colloquial expressions, comparisons, conditionals, and 0.8% code-mixed tokens (English + Southeast Asian languages).
Multi-domain: Covers diverse product verticals from a major English-language e-commerce platform in Southeast Asia.

We also propose a *two-stage propose-and-verify framework for robust quad extraction:
1️⃣ High-recall candidate generation under strict schema constraints.
2️⃣ Explicit verification of grounding, scope, and modality, followed by review-level consolidation to reduce hallucinations and scope leakage in long texts.

✅ Results: Our method consistently outperforms single-stage prompting (with/without chain-of-thought) and strong ABSA baselines across multiple Qwen3 model sizes, achieving higher quad-level micro-F1* and improved robustness on discourse-hard cases (e.g., comparisons, conditionals).
