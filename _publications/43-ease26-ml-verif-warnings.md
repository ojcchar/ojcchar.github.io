---
collection: publications
permalink: /publications/43-ease26-ml-verif-warnings

title: "Verifier Warnings Do Not Improve Comprehensibility Prediction"
authors: "<u>Nadeeshan De Silva</u>, Martin Kellogg, **Oscar Chaparro**"
venue_key: "ease26"
track: 
pages: "(to appear)"
date: 2026-04-04
doiurl: 

paperurl: 
package: 
notes: 
distinction: 
toolurl: 
---

**Abstract:** Proponents of software verification suggest that code simplicity is linked to the effort to verify code, hypothesizing that formal verifiers produce fewer false positive warnings and require less manual intervention when analyzing simpler code. A recent meta-analysis study found empirical support for this hypothesis: a small correlation between the sum of verifier warnings and human-derived code comprehensibility metrics. Based on this finding, we conjectured that using the sum of verifier tool (verifier) warnings to represent program semantic information as an input feature to machine learning (ML) models for code comprehensibility prediction can enhance their performance, when combined with traditional syntactic and developer features. 

To test this conjecture, we performed a control-treatment experiment incorporating the verifier warning sum feature into machine learning models from the literature, and conducted a comparative analysis of their performance against models trained only on syntactic and developer features. We found no significant difference in the prediction performance of models with and without the warnings feature. Our findings suggest that while a correlation exists, the verifier warning sum offers limited discriminative power: combining syntactic and developer features is just as effective for predicting human-judged code comprehensibility.
