---
collection: publications
permalink: /publications/16-fse20-bee

title: "BEE: A Tool for Structuring and Analyzing Bug Reports"
authors: "Yang Song*, **Oscar Chaparro**"
venue_key: "fse20"
track: Tool demo track
pages: "1551-1555"
date: 2020-11-01
doiurl: https://doi.org/10.1145/3368089.3417928

paperurl: /files/16-fse20-bee.pdf
package: https://github.com/sea-lab-wm/bee-tool/tree/master/fse20-evaluation
notes: 
distinction: 
toolurl: https://github.com/sea-lab-wm/bee-tool
---

**Abstract:** This paper introduces BEE, a tool that automatically analyzes user-written bug reports and provides feedback to reporters and developers about the system’s observed behavior (OB), expected behavior (EB), and the steps to reproduce the bug (S2R). BEE employs machine learning to (i) detect if an issue describes a bug, an enhancement, or a question; (ii) identify the structure of bug descriptions by automatically labeling the sentences that correspond to the OB, EB, or S2R; and (iii) detect when bug reports fail to provide these elements. BEE is integrated with GitHub and offers a public web API that researchers can use to investigate bug management tasks based on bug reports. We evaluated BEE’s underlying models on more than 5k existing bug reports and found they can correctly detect OB, EB, and S2R sentences as well as missing information in bug reports. BEE is an open-source project that can be found at https://git.io/JfFnN. A screencast showing the full capabilities of BEE can be found at https://youtu.be/8pC48f_hClw.