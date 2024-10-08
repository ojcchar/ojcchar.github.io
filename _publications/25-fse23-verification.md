---
collection: publications
permalink: /publications/25-fse23-verification

title: "On the Relationship between Code Verifiability and Understandability"
authors: "<u>Kobi Feldman</u>, Martin Kellogg, and **Oscar Chaparro**"
venue_key: fse23
track:
pages: "211–223"
date: 2023-11-01
doiurl: https://doi.org/10.1145/3611643.3616242

paperurl: /files/25-fse23-verification.pdf
package: https://zenodo.org/record/8237328
notes:
toolurl: 
---

**Abstract:** Proponents of software verification have argued that simpler code is easier to verify: that is, that verification tools issue fewer false positives and require less human intervention when analyzing simpler code. We empirically validate this assumption by comparing the number of warnings produced by four state-of-the-art verification tools on 211 snippets of Java code with 20 metrics of code comprehensibility from human subjects in six prior studies. Our experiments, based on a statistical (meta-)analysis, show that, in aggregate, there is a small correlation (r = 0.23) between understandability and verifiability. The results support the claim that easy-to-verify code is often easier to understand than code that requires more effort to verify. Our work has implications for the users and designers of verification tools and for future attempts to automatically measure code comprehensibility: verification tools may have ancillary benefits to understandability, and measuring understandability may require reasoning about semantic, not just syntactic, code properties.
