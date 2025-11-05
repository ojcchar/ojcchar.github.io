---
collection: publications
permalink: /publications/39-icsme25-gui-bl

title: "LadyBug: A GitHub Bot for UI-Enhanced Bug Localization in Mobile Apps"
authors: "Junayed Mahmud, James Chen, Terry Achille, Camilo Alvarez-Velez, Darren Dean Bansil, Patrick Ijieh, Samar Karanch, <u>Nadeeshan De Silva</u>, **Oscar Chaparro**, Andrian Marcus, and Kevin Moran"
venue_key: "icsme25"
track: Tool demo track
pages: "940-944"
date: 2025-07-01
doiurl: https://doi.org/10.1109/ICSME64153.2025.00111

paperurl: /files/39-icsme25-gui-bl.pdf
package: 
notes: 
distinction: 
toolurl: https://github.com/LadyBugML/ladybug
---

**Abstract:** This paper introduces LadyBug, a GitHub bot that automatically localizes bugs for Android apps by combining UI interaction information with text retrieval. LadyBug connects to an Android app’s GitHub repository, and is triggered when a bug is reported in the corresponding issue tracker. Developers can then record a reproduction trace for the bug on a device or emulator and upload the trace to LadyBug via the GitHub issue tracker. This enables LadyBug to utilize both the text from the original bug description, and UI information from the reproduction trace to accurately retrieve a ranked list of files from the project that most likely contain the reported bug. We empirically evaluated LadyBug using an automated testing pipeline and benchmark called RedWing that contains 80 fully-localized and reproducible bug reports from 39 Android apps. Our results illustrate that LadyBug outperforms text-retrieval based baselines and that the utilization of GUI information leads to a substantial increase in localization accuracy. LadyBug is an open-source tool, available at https://github.com/LadyBugML/ladybug