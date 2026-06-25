---
collection: publications
permalink: /publications/44-ase26-bias_vlms

title: "Pattern Over Pixels: Measuring Pattern Completion Bias in Multimodal Code Generation"
authors: "Khai Nguyen, **Oscar Chaparro**, and Antonio Mastropaolo"
venue_key: "ase26"
track: 
pages: "(to appear)"
date: 2026-06-01
doiurl: 

paperurl: 
package: 
notes: 
distinction: 
toolurl: 
---

**Abstract:** Multimodal large language models (MLLMs) are increasingly used to translate webpage screenshots into front-end code, but repeated UI patterns may sway them toward visually incorrect yet pattern-consistent outputs. In this work, we test how repeated webpage patterns hurt MLLM accuracy on an objective screenshot-to-code fill-in-the-blank task. We introduce the first benchmark for visual pattern-completion bias, where one localized element in a repeated UI pattern is perturbed and the model must recover the masked width or font-size value from the screenshot and HTML context. Starting from 30 webpages curated from Design2Code, we built 1,440 evaluated screenshots spanning structural card and text-style patterns under standard and noise-overlaid conditions. We evaluate five frontier MLLMs and find that all are strongly biased toward the repeated baseline. Mean bias rate reaches 69.61% on card-width perturbations and 80.22% on text font-size perturbations, while mean accuracy is only 23.11% and 7.89%, respectively. Codex-5.3 performs best but still drops from 65.83% accuracy on cards to 13.89% on text, while Flash-3.0 reaches 96.11% bias on text. Noise, subtler perturbations, and boundary positions further increase bias rate. Reasoning analysis further shows that greater reasoning effort reduces bias, yet qualitative evidence reveals that models can identify the anomalous element and still override it with the pattern-consistent answer. Our results identify a concrete failure mode in multimodal code generation and show that its severity is governed by visual saliency.