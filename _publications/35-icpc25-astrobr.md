---
collection: publications
permalink: /publications/35-icpc25-astrobr

title: "Combining Language and App UI Analysis for the Automated Assessment of Bug Reproduction Steps"
authors: "Junayed Mahmud, <u>Antu Saha</u>, **Oscar Chaparro**, Kevin Moran, and Andrian Marcus"
venue_key: "icpc25"
track: 
pages: "to appear"
date: 2025-04-04
doiurl: 

paperurl: /files/35-icpc25-astrobr.pdf
package: https://github.com/sea-lab-wm/AstroBR-Bug-Reproduction-Steps-Assessment
notes: 
distinction: 
---

**Abstract:** Bug reports are essential for developers to confirm software problems, investigate their causes, and validate fixes. Unfortunately, reports often miss important information or are written unclearly, which can cause delays, increased issue resolution effort, or even the inability to solve issues. One of the most common components of reports that are problematic is the steps to reproduce the bug(s) (S2Rs), which are essential to replicate the described program failures and reason about fixes. Given the proclivity for deficiencies in reported S2Rs, prior work has proposed techniques that assist reporters in writing or assessing the quality of S2Rs. However, automated understanding of S2Rs is challenging, and requires linking nuanced natural language phrases with specific, semantically related program information. Prior techniques often struggle to form such language <-> program connections – due to issues in language variability and limitations of information gleaned from program analyses.
To more effectively tackle the problem of S2R quality annotation, we propose a new technique called AstroBR, which leverages the language understanding capabilities of LLMs to identify and extract the S2Rs from bug reports and map them to GUI interactions in a program state model derived via dynamic analysis. We compared AstroBR to a related state-of-the-art approach and we found that AstroBR annotates S2Rs 25.2% better (in terms of F1 score) than the baseline. Additionally, AstroBR suggests more accurate missing S2Rs than the baseline (by 71.4% in terms of F1 score).
