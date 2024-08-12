---
collection: publications
permalink: /publications/31-issta24-ui-bl

title: "Toward the Automated Localization of Buggy Mobile App UIs from Bug Descriptions"
authors: "<u>Antu Saha</u>, <u>Yang Song</u>, Junayed Mahmud, Ying Zhou, Kevin Moran, and **Oscar Chaparro**"
venue_key: "issta24"
track: 
pages: "(to appear)"
date: 2024-09-02
doiurl: https://doi.org/10.1145/3650212.3680357

paperurl: /files/31-issta24-ui-bl.pdf
package: https://zenodo.org/doi/10.5281/zenodo.12669080
notes: 
distinction: 
---

**Abstract:** Bug report management is a costly software maintenance process comprised of several challenging tasks. Given the UI-driven nature of mobile apps, bugs typically manifest through the UI, hence the identification of buggy UI screens and UI components (Buggy UI Localization) is important to localizing the buggy behavior and eventually fixing it. However, this task is challenging as developers must reason about bug descriptions (which are often low-quality), and the visual or code-based representations of UI screens.

This paper is the first to investigate the feasibility of automating the task of Buggy UI Localization through a comprehensive study that evaluates the capabilities of one textual and two multi-modal deep learning (DL) techniques and one textual unsupervised technique. We evaluate such techniques at two levels of granularity, Buggy UI Screen and UI Component localization. Our results illustrate the individual strengths of models that make use of different representations, wherein models that incorporate visual information perform better for UI screen localization, and models that operate on textual screen information perform better for UI component localization – highlighting the need for a localization approach that blends the benefits of both types of techniques. Furthermore, we study whether Buggy UI Localization can improve traditional buggy code localization, and find that incorporating localized buggy UIs leads to improvements of 9%-12% in Hits@10.