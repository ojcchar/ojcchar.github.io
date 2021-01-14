---
collection: publications
permalink: /publications/17-saner21-qrex

title: "Combining Query Reduction and Expansion for Text-Retrieval-Based Bug Localization"
authors: "Juan Manuel Florez, **Oscar Chaparro**, Christoph Treude, and Andrian Marcus"
venue_key: "saner21"
track: 
pages: "(to appear)"
date: 2021-03-01
doiurl: 

paperurl: /files/17-saner21-qrex.pdf
package: https://doi.org/10.5281/zenodo.4431018
notes: 
distinction: 
---

**Abstract:** Automated text-retrieval-based bug localization (TRBL) techniques normally use the full text of a bug report to formulate a query and retrieve parts of the code that are buggy. Previous research has shown that reducing the size of the query increases the effectiveness of TRBL. On the other hand, researchers also found improvements when expanding the query (i.e., adding more terms). In this paper, we bring these two views together to reformulate queries for TRBL. Specifically, we improve discourse-based query reduction strategies, by adopting a combinatorial approach and using task phrases from bug reports, and combine them with a state-of-the-art query expansion technique, resulting in 970 query reformulation strategies. We investigate the benefits of these strategies for localizing buggy code elements and define a new approach, called QREX, based on the most effective strategy. We evaluated the reformulation strategies, including QREX, on 1,217 queries from different software systems to retrieve buggy code artifacts at three code granularities, using five state-of-the-art automated TRBL approaches. The results indicate that QREX increases TRBL effectiveness by 4% - 12.6%, compared to applying query reduction and expansion in isolation, and by 32.1%, compared to the no-reformulation baseline.