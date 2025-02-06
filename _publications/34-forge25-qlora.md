---
collection: publications
permalink: /publications/34-forge25-qlora

title: "Resource-Efficient & Effective Code Summarization"
authors: "Saima Afrin, Joseph Call, Khai Nguyen, **Oscar Chaparro**, and Antonio Mastropaolo"
venue_key: "forge25"
track: 
pages: "to appear"
date: 2025-04-03
doiurl: 

paperurl: /files/34-forge25-qlora.pdf
package: https://github.com/saimaafrin/QLoRA-Code-Summarization
notes: 
distinction: 
---

**Abstract:** Code Language Models (CLMs) have demonstrated high effectiveness in automating software engineering tasks such as bug fixing, code generation, and code documentation. This progress has been driven by the scaling of large models, ranging from millions to trillions of parameters (e.g., GPT-4). However, as models grow in scale, sustainability concerns emerge, as they are extremely resource-intensive, highlighting the need for efficient, environmentally conscious solutions. GreenAI techniques, such as QLoRA (Quantized Low-Rank Adaptation), offer a promising path for dealing with large models’ sustainability as they enable resource-efficient model fine-tuning. Previous research has shown the effectiveness of QLoRA in code-related tasks, particularly those involving natural language inputs and code as the target output (NL-to-Code), such as code generation. However, no studies have explored its application to tasks that are fundamentally similar to NL-to-Code (natural language to code) but operate in the opposite direction, such as code summarization. This leaves a gap in understanding how well QLoRA can generalize to Code-to-NL tasks, which are equally important for supporting developers in understanding and maintaining code. To address this gap, we investigate the extent to which QLoRA’s capabilities in NL-to-Code tasks can be leveraged and transferred to code summarization, one representative Code-to-NL task. Our study evaluates two state-of-the-art CLMs (CodeLlama and DeepSeek-Coder) across two programming languages: Python and Java. Each model was tasked with generating a meaningful description for Python and Java code methods. The findings of our research confirm previous patterns that emerged when applying QLoRA to source code generation. Notably, we observe that QLoRA not only allows efficient fine-tuning of CLMs for code summarization but also achieves the best results with minimal parameter adjustment compared to full model fine-tuning, which requires expensive recalibration of all model parameters in the traditional fine-tuning process.
