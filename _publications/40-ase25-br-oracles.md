---
collection: publications
permalink: /publications/40-ase25-br-oracles

title: "Generating Failure-Based Oracles to Support Testing of Reported Bugs in Android Apps"
authors: "Jack Johnson, Junayed Mahmud, **Oscar Chaparro**, Kevin Moran, and Mattia Fazzini"
venue_key: "ase25"
track: 
pages: "to appear"
date: 2025-08-01
doiurl: 

paperurl: /files/40-ase25-br-oracles.pdf
package: https://zenodo.org/records/15556567
notes: 
distinction: 
toolurl: 
---

**Abstract:** In the context of mobile apps, bug report management tasks have been shown to be among the most time-consuming and intellectually intensive software maintenance activities. As such, researchers have developed tools to automate the reproduction, validation, and localization of reported bugs. However, one complex, time-consuming, and important task that lacks automated support is the creation of test oracles for reported functional failures that manifest through the GUI. This is challenging task--requiring nuanced, multi-modal reasoning about bug descriptions, affected GUI components, and the characteristics of the related erroneous program state(s).

To explore the feasibility of automating this task, we conduct a empirical investigation into how the multi-modal (i.e., text and GUI-related code) reasoning capabilities of Large Language Models (LLMs) can be used to automatically generate assertion-based test oracles for non-crashing, functional failures described in Android app bug reports. Building upon the findings of this study, we construct and evaluate AndroB2O, an automated, LLM-based approach that, given a bug report and the GUI screen associated with the reported failure as inputs, generates failure-based oracles (FBOs) in the form of test assertions. The approach first identifies the GUI elements related to the failure and then defines assertions that aim to confirm the absence of the failure based on the elements' properties. To evaluate AndroB2O, we create the first dataset of Android bug reports containing test cases with GUI interactions and test oracles that reveal reported failures. The results of our evaluation on 152 failures show that AndroB2O is able to generate FBOs that successfully identify the failure (and hence can confirm it's absence) in 61.2% of the cases. We integrated AndroB2O with ReBL, a failure reproduction tool, to evaluate its effectiveness in automated generation of test cases complete with oracles for reported failures, and obtained promising results.