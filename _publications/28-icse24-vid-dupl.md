---
collection: publications
permalink: /publications/28-icse24-vid-dupl

title: "Semantic GUI Scene Learning and Video Alignment for Detecting  Duplicate Video-based Bug Reports"
authors: "Yanfu Yan, Nathan Cooper, **Oscar Chaparro**, Kevin Moran, and Denys Poshyvanyk"
venue_key: "icse24"
track: 
pages: "(to appear)"
date: 2024-04-03
doiurl: https://doi.org/10.1145/3597503.3639163

paperurl: /files/28-icse24-vid-dupl.pdf
package: https://doi.org/10.5281/zenodo.10455811
notes: 
distinction: 
---

**Abstract:** Video-based bug reports are increasingly being used to document bugs for programs centered around a graphical user interface (GUI). However, developing automated techniques to manage video-based reports is challenging as it requires identifying and understanding often nuanced visual patterns that capture key information about a reported bug. In this paper, we aim to overcome these challenges by advancing the bug report management task of duplicate detection for video-based reports. To this end, we introduce a new approach, called Janus, that adapts the scene-learning capabilities of vision transformers to capture subtle visual and textual patterns that manifest on app UI screens — which is key to differentiating between similar screens for accurate duplicate report detection. Janus also makes use of a video alignment technique capable of adaptive weighting of video frames to account for typical bug manifestation patterns. In a comprehensive evaluation on a benchmark containing 7,290 duplicate detection tasks derived from 270 video-based bug reports from 90 Android app bugs, the best configuration of our approach achieves an overall mRR/mAP of 89.8%/84.7%, and for the large majority of duplicate detection tasks, outperforms prior work by ≈9% to a statistically significant degree. Finally, we qualitatively illustrate how the scene-learning capabilities provided by Janus benefits its performance.
