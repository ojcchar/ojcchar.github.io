---
collection: publications
permalink: /publications/18-icse21-tango

title: "It Takes Two to Tango: Combining Visual andTextual Information for Detecting DuplicateVideo-Based Bug Reports"
authors: " Nathan Cooper, Carlos Bernal-Cárdenas, **Oscar Chaparro**, Kevin Moran, Denys Poshyvanyk"
venue_key: "icse21"
track: 
pages: "(to appear)"
date: 2021-05-01
doiurl: 

paperurl: /files/18-icse21-tango.pdf
package:
notes: 
distinction: 
---

**Abstract:** When a bug manifests in a user-facing application, it is likely to be exposed through the graphical user interface (GUI). Given the importance of visual information to the process of identifying and understanding such bugs, users are increasingly making use of screenshots and screen-recordings as a means to report issues to developers. However, when such information is reported en masse, such as during crowd-sourced testing, managing these artifacts can be a time-consuming process. As the reporting of screen-recordings in particular becomes more popular, developers are likely to face challenges related to manually identifying videos that depict duplicate bugs. Due to their graphical nature, screen-recordings present challenges for automated analysis that preclude the use of current duplicate bug report detection techniques. To overcome these challenges and aid developers in this task, this paper presents TANGO, a duplicate detection technique that operates purely on video-based bug reports by leveraging both visual and textual information. TANGO processes this data using a combination of tailored computer vision techniques, optical character recognition, and text retrieval. We evaluated multiple configurations of TANGO in a comprehensive empirical evaluation on 4,860 duplicate detection tasks that involved a total of 180 screen-recordings from six Android apps. Additionally, we conducted a user study investigating the effort required for developers to manually detect duplicate video-based bug reports and compared this to the effort required to use TANGO. The results reveal that TANGO’s optimal configuration is highly effective at detecting duplicate video-based bug reports, accurately ranking target duplicate videos in the top- 2 returned results in 83% of cases. Additionally, our user study shows that, on average, TANGO can reduce developer effort by over 60%, illustrating its practicality.