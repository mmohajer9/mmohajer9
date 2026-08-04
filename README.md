<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:0072ff,100:8E2DE2&height=210&section=header&text=Shipping%20and%20Doubting%20LLMs&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=A%20Longitudinal%20Case%20Study%20of%20One%20Engineer&descAlignY=58&descSize=18" width="100%" alt="Shipping and Doubting LLMs — A Longitudinal Case Study of One Engineer" />

<div align="center">

### 👨‍💻 Mohammad Mahdi Mohajer

*Senior ML Engineer, [LRQA](https://www.lrqa.com/) · ML × SE Researcher · Toronto, Canada 🇨🇦*

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1100&center=true&vCenter=true&width=620&color=0072FF&lines=Ships+production+LLM+systems+%F0%9F%8F%97%EF%B8%8F;Publishes+peer-reviewed+doubts+about+them+%F0%9F%94%AC;290%2B+citations+%C2%B7+h-index+7+%F0%9F%93%8A;10+years+of+full-stack+underneath+the+ML+%E2%9A%A1" alt="Ships production LLM systems · Publishes peer-reviewed doubts about them" />

[![Citations](https://img.shields.io/badge/📚_Citations-290%2B-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en)
[![h-index](https://img.shields.io/badge/📈_h--index-7-34A853?style=for-the-badge)](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en)

</div>

> 🧾 **Abstract.** This profile documents a long-running case study of one senior AI engineer with an unusual dual condition. By day, the subject ships production LLM systems. By night, he publishes peer-reviewed research asking whether those systems work as well as everyone claims. Symptoms include a decade of full-stack engineering, a growing publication record in software engineering venues, and a stubborn refusal to accept *"it looks fine"* as an evaluation method. The two conditions turn out to help each other: each one treats the failure modes of the other. The condition is stable, productive, and shows no exit criteria (see Fig. 1).

**🏷️ Index Terms:** `large language models` · `software testing` · `benchmarking` · `program analysis` · `production ML systems`

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00c6ff,50:0072ff,100:8E2DE2&height=3" width="100%" alt="" />

## 1️⃣ Introduction

Most engineers **ship** AI systems. Most researchers **doubt** them. I do both, and I'm convinced neither works without the other.

At **LRQA** 🏗️ I build everything around the model: retrieval, evaluation pipelines, and the full-stack product that turns an LLM into something people can rely on. On the research side 🔬, I build benchmarks and testing methods that check whether any of it actually holds up, including work on how well LLMs handle real-world software engineering tasks.

```mermaid
flowchart LR
    A(["🏗️ Ship LLM systems"]) --> B(["🤨 Doubt them"])
    B --> C(["🔬 Benchmark and test"])
    C --> D(["📄 Publish findings"])
    D --> E(["💡 Ship them better"])
    E --> A
    style A fill:#00c6ff,stroke:#0072ff,color:#0f172a
    style B fill:#009bf5,stroke:#0072ff,color:#ffffff
    style C fill:#0072ff,stroke:#0057c2,color:#ffffff
    style D fill:#4a4fe4,stroke:#3730a3,color:#ffffff
    style E fill:#8e2de2,stroke:#6b21a8,color:#ffffff
    linkStyle default stroke:#0072ff,stroke-width:2px
```

<div align="center"><sub><b>Figure 1.</b> The subject's core feedback loop. No exit condition has been observed.</sub></div>

## 2️⃣ Related Work

The subject's peer-reviewed work covers benchmarks for LLM coding ability, testing methods for deep learning libraries, and LLM-driven program analysis. The full record is archived in [[3]](#references) 📚. His industry track record is documented separately in [[2]](#references) 💼.

## 3️⃣ Apparatus — the stack 🧰

**🧠 ML & LLMs:** model training, evaluation, and everything needed to trust the outputs

<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn&perline=8" alt="Python, PyTorch, TensorFlow, scikit-learn" />

**🖥️ Product & Backend:** because a model without a product around it is just a demo

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,django,nodejs,graphql&perline=8" alt="TypeScript, React, Next.js, Django, Node.js, GraphQL" />

**☁️ Infra & Data:** keeping things alive in production, where "it worked on my machine" goes to die

<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,postgres,redis,nginx&perline=8" alt="Docker, Kubernetes, AWS, PostgreSQL, Redis, Nginx" />

**⚗️ Evaluation criterion:** every claim gets a benchmark and every system gets a test. Vibes are not a metric.

## 4️⃣ Threats to Validity

⚠️ This README was written by the subject himself. Independent replication is encouraged: read the papers [[3]](#references) 📄, run the [code](https://github.com/mmohajer9?tab=repositories) 💻, or email him [[5]](#references) ✉️ and draw your own conclusions.

## References

| # | Directory | Contents |
|---|---|---|
| [1] | 🌐 **[mamad.ai](https://mamad.ai/)** | The subject's homepage |
| [2] | 💼 **[LinkedIn](https://www.linkedin.com/in/mmohajer9/)** | Industry track record, independently documented |
| [3] | 📚 **[Google Scholar](https://scholar.google.ca/citations?user=GtTTkj0AAAAJ&hl=en)** | Peer-reviewed publications, fully archived |
| [4] | 🧩 **[Stack Overflow](https://stackoverflow.com/users/9091011)** | Answers left in the wild |
| [5] | ✉️ **[contact@mamad.ai](mailto:contact@mamad.ai)** | Correspondence. Hard problems preferred |

## 📖 How to Cite

```bibtex
@misc{mohajer2026,
  author  = {Mohajer, Mohammad Mahdi},
  title   = {Available for interesting problems in LLM systems and SE research},
  contact = {contact@mamad.ai},
  url     = {https://mamad.ai},
  note    = {Toronto, Canada. Responds faster to hard problems than easy ones.}
}
```

## 🙏 Acknowledgments

This research was supported by **coffee** ☕. Grants are accepted via:

<a href="https://www.buymeacoffee.com/mmohajer9"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="40" alt="Buy Me a Coffee" /></a>
&nbsp;
<a href="https://ko-fi.com/mmohajer9"><img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="40" alt="Ko-fi" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:0072ff,100:8E2DE2&height=110&section=footer" width="100%" alt="" />
