---
collection: publications
permalink: /publications/46-issta26-apr-ui-bugs

title: "Automated Program Repair for UI-centric Android Bugs: How Far are We?"
authors: "Junayed Mahmud, Sparsh Pandey, <u>Nadeeshan De Silva</u>, Atish Kumar Dipongkor, JingJing Wu, **Oscar Chaparro**, Mattia Fazzini, and Kevin Moran"
venue_key: "issta26"
track: 
pages: "(to appear)"
date: 2026-06-02
doiurl: 

paperurl: 
package: 
notes: 
distinction: 
---

**Abstract:** Substantial research effort has been devoted to developing techniques for automated program repair (APR) that suggest patches for localized buggy code -- and more recent techniques have begun to leverage the capabilities of code-centric large language models (LLMs). However, the scope and diversity of bugs to which these techniques have historically been applied is limited. In particular, the research community currently lacks a comprehensive understanding of the performance of APR techniques on bugs that arise in UI-centric programs, such as mobile apps. Bugs in UI centric programs carry with them unique challenges, including (i) the need to reason across interconnected subroutines that connect presentation and program logic, (ii) event driven programming paradigms, and (iii) the need to reason about program state through cues in the UI.

In this paper, we investigate the effectiveness of existing APR techniques when applied to fix bugs in UI-centric programs -- specifically Android applications. To explore this phenomenon, we conduct a comprehensive empirical study with five existing program repair techniques (including those that utilize LLMs) on a hybrid dataset including 46 synthetic bugs, generated via an Android-specific mutation tool, and 25 real bugs systematically mined from issue reports of 13 popular Android applications. Our findings illustrate important current limitations in resolving UI-related issues in mobile apps. We synthesize these results to form a taxonomy of the limitations of existing program repair techniques. This taxonomy details important limitations and can inform future research efforts in designing automated program repair tools for UI-centric bugs in mobile apps.
