# ID-SPAM: Leveraging Self-Attention for Input-Dependent Soft Prompting in LLMs

This repository contains supporting material for understanding and presenting the paper:

> **Leveraging Self-Attention for Input-Dependent Soft Prompting in LLMs (ID-SPAM)**  
> Authors: Ananth Muppidi, Abhilash Nandy, Sambaran Bandyopadhyay

The repo bundles together a slide deck, a video walkthrough, and a Medium article that explain the core ideas of ID-SPAM in an accessible way.


## 📌 Quick Links

| Resource           | Link |
|--------------------|------|
| Original Paper     | [arXiv: Leveraging Self-Attention for Input-Dependent Soft Prompting in LLMs](https://arxiv.org/abs/2506.05629) |
| Medium Article     | _[Add your Medium article link here]_ |
| Presentation Video | _[Add your YouTube walkthrough link here]_ |



## 🧠 Project Overview

This project focuses on the ID-SPAM method (Input Dependent Soft Prompting with a self-Attention Mechanism), a parameter-efficient fine-tuning technique for large language models.

At a high level, ID-SPAM:
- Generates **input-dependent soft prompts** using self-attention over input embeddings and a small MLP.
- Keeps the **backbone LLM frozen**, training only a lightweight prompt generator.
- Achieves strong performance on **GLUE**, **SuperGLUE**, and **zero-shot transfer** benchmarks compared to other soft-prompt and PEFT baselines.

This repository packages explanations of the method in three formats: slides, video, and a Medium article.


---

```markdown
## 🎤 Slide Deck (PPT)

The slide deck provides a concise, talk-ready overview of the paper, suitable for a 10–15 minute presentation. It typically covers:

1. Motivation and background (PEFT, soft prompts)
2. Limitations of static soft prompts
3. The ID-SPAM idea and architecture
4. Experimental setup and benchmarks
5. Results on GLUE / SuperGLUE
6. Zero-shot transfer and ablations
7. Limitations and future work
8. Key takeaways

You can use the PPT directly for class presentations, demos, or as a base to create your own customized slides.


## 📝 Medium Article

The Medium article is a narrative-style explanation of ID-SPAM aimed at a broader technical audience (students, ML practitioners, engineers).

It walks through:
- Hard vs. soft prompts in intuitive terms  
- Why input-dependent prompts are needed  
- The ID-SPAM pipeline step by step  
- High-level experimental results and what they mean in practice  
- Practical implications, limitations, and potential future directions

> 🔗 **Medium Article:** _[Add your Medium article link here]_


## ▶️ Video Walkthrough

The YouTube video is a recorded walkthrough of the slide deck. It is useful if you prefer:

- Listening to an explanation rather than reading the paper  
- Using it as a teaching or seminar resource  
- Replaying sections while reviewing the slides

The video generally follows the slide structure and ends with a short discussion and summary.

> 🎥 **YouTube Presentation:** _[Add your YouTube walkthrough link here]_
```

## 📚 Original Paper

For technical details and citation, please refer to the original work:

> **Leveraging Self-Attention for Input-Dependent Soft Prompting in LLMs (ID-SPAM)**  
> Ananth Muppidi, Abhilash Nandy, Sambaran Bandyopadhyay  
> arXiv: https://arxiv.org/abs/2506.05629


## 🙏 Acknowledgements

- All core ideas, algorithms, and experimental results are due to **Muppidi et al.**, the authors of the ID-SPAM paper.
- Any figures or tables derived from the paper should respect the licensing terms specified on the arXiv / ACL pages.
- This repository focuses on explaining and presenting the work, not on claiming any new algorithmic contribution.


## 💬 Feedback & Contributions

Suggestions and improvements are welcome. You can:

- Open an issue with corrections or enhancement ideas  
- Submit a pull request (e.g., improved slides, extra notes, or code implementations)  
- Share feedback via the Medium article or YouTube comments

The goal is to make the ID-SPAM paper easier to **understand, teach, and present**, so any contributions that improve clarity and accessibility are appreciated.
