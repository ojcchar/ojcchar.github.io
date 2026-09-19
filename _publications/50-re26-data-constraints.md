---
collection: publications
permalink: /publications/50-re26-data-constraints

title: "Towards the Automated Identification of Data Constraints in Software Documents"
authors: "Ying Zhou, Miao Miao, Vlad Birsan, **Oscar Chaparro**, Shiyi Wei, and Andrian Marcus"
venue_key: "re"
track: 
volume: 
pages: "(to appear)"
date: 2026-06-14
doiurl: 

paperurl: 
package: 
notes: 
distinction: 
toolurl: 
---

**Abstract:** Data constraints are important business rules that specify the values allowed or required for the data used in a software system. These constraints are typically described in textual software artifacts (e.g., requirements, developer documents, user manuals, etc.). In this paper, we focus on automating the task of identifying data constraints in natural language software documents. In order to automate this task, we first study how data constraints are described in natural language. Specifically, we studied 546 data constraints described in the natural language artifacts of nine software systems. We uncovered and documented nine linguistic discourse patterns that stakeholders use to describe data constraints in natural language. We cast the constraint identification and extraction as a text matching and classification problem. We explore the suitability of traditional machine learning techniques, using the discourse patterns we discovered, together with other linguistic elements, as features, for automatically classifying sentence fragments as data constraint descriptions. The best combination of features and learner achieves 63.63% precision and 61.40% recall (62.34% F1). Automating the extraction of data constraints from natural language text is essential for automating their traceability to code, test generation, compliance analysis, etc.
