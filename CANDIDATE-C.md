<div align="center">

# Shipping and Doubting Large Language Models:<br>A Longitudinal Case Study of One Engineer

**Mohammad Mahdi Mohajer**

*Senior ML Engineer, LRQA · ML/SE Researcher · Toronto, Canada*

[**Website**](https://mamad.ai/) · [**Google Scholar**](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en) · [**LinkedIn**](https://www.linkedin.com/in/mmohajer9/) · [**Email**](mailto:contact@mamad.ai)

</div>

> **Abstract** — We present a longitudinal study of a senior AI engineer who ships production LLM systems by day and publishes peer-reviewed doubts about them by night. The subject exhibits a rare dual condition: full-stack engineering pragmatism (10 years, symptoms include Python, TypeScript, and an unreasonable affection for clean architecture) combined with academic skepticism (290+ citations, h-index 7). Contributions include SWE-Bench+, a benchmark that revealed leading LLM coding results were partly built on leaked data. Evaluation across industry and academia suggests the two conditions are not in conflict; rather, each is the treatment for the other's failure modes.

**Index Terms** — large language models, software testing, benchmarking, program analysis, production ML systems

## 1. Introduction

Most engineers ship AI systems. Most researchers question them. I do both, and I'm convinced neither works without the other.

At **[LRQA](https://www.lrqa.com/)** I build production LLM systems — the retrieval, the evaluation pipelines, and the full-stack product around the model. In my research life, I build the benchmarks and testing methods that check whether any of it actually holds up.

## 2. Selected Publications

| Contribution | Venue | Impact |
|---|---|---|
| **[SWE-Bench+: Enhanced Coding Benchmark for LLMs](https://arxiv.org/abs/2410.06992)** | 2024 | 120+ citations |
| **Effectiveness of ChatGPT for Static Analysis: How Far Are We?** | AIware 2024 | 85+ citations |
| **History-Driven Fuzzing for Deep Learning Libraries** | ACM TOSEM | — |
| **Program Slicing in the Era of Large Language Models** | IEEE COMPSAC 2025 | — |
| **Evaluating API-Level Deep Learning Fuzzers** | ACM TOSEM 2026 | — |

Full list: [Google Scholar](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en)

## 3. Systems & Artifacts

- **[video-to-ui](https://github.com/mmohajer9/video-to-ui)** — a Claude Code skill that turns a UI screen recording into design data, code edits, or a runnable React scaffold.
- **[RESTester](https://github.com/mmohajer9/RESTester)** — automatic black-box test-case generator for RESTful APIs (+ its [Testing-as-a-Service backend](https://github.com/mmohajer9/RESTester-TaaS)).
- **[pyccmetrics](https://github.com/mmohajer9/pyccmetrics)** — Python package for code-complexity metrics.

## 4. Methodology

```text
ML/LLMs ......... Python, PyTorch, TensorFlow, scikit-learn
Product ......... TypeScript, React, Next.js, Django, Node.js
Infrastructure .. Docker, Kubernetes, AWS, PostgreSQL, Redis
Evaluation ...... if it isn't tested, it doesn't work — it just hasn't failed yet
```

## 5. Threats to Validity

This README was written by the subject himself. Independent replication is encouraged: read the [papers](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en), run the [code](https://github.com/mmohajer9?tab=repositories), or [email him](mailto:contact@mamad.ai) and form your own conclusions.

## How to Cite

```bibtex
@misc{mohajer2026,
  author  = {Mohajer, Mohammad Mahdi},
  title   = {Available for interesting problems in LLM systems and SE research},
  contact = {contact@mamad.ai},
  url     = {https://mamad.ai},
  note    = {Toronto, Canada. Responds faster to hard problems than easy ones.}
}
```

## Acknowledgments

This research was supported by coffee. Grants are accepted via [Buy Me a Coffee](https://www.buymeacoffee.com/mmohajer9) and [Ko-fi](https://ko-fi.com/mmohajer9).
