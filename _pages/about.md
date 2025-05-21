---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor of [Computer Science](https://www.wm.edu/as/computerscience/?svr=web){:target="_blank"} at [William & Mary](https://www.wm.edu/){:target="_blank"}. 

I lead the [**S**oftware **E**volution and **A**nalysis (**SEA**)](lab/) Lab, which conducts research in software maintenance & evolution, program comprehension, refactoring, software quality, developers’ productivity, text analysis applied to software engineering (SE), software supply chain management, and legal aspects of SE.

My **current research areas** are:
1. <u>Automated bug report management</u>: automating bug reporting, triage, localization, and resolution
2. <u>Verification-guided code refactoring and comprehension</u>: leveraging code verification techniques to guide automated code refactoring and reduce code comprehension effort
3. <u>Informed decision making for software change</u>: processing and managing code change decisions documented in software artifacts/repositories to assist developers in producing software that is less faulty, higher quality, and easier to maintain
4. <u>Software licensing and supply chain management</u>: automating and managing the software supply chain (emphasis on licensing and software evolution)

My research employs **empirical methods**, analyzes/leverages **different software artifacts** (software bug reports, source code, online discussions, etc.), and builds on **creating, adapting, and integrating techniques** based on program analysis, software repository mining (MSR), information retrieval (IR), natural language processing (NLP), computer vision (CV), and machine/deep learning (ML/DL).

Take a look at my [publications](publications/) to know more about my research.

**Education**: I got my Ph.D. in Software Engineering (SE) from [The University of Texas at Dallas](http://www.utdallas.edu/){:target="_blank"} in 2019, under the advice of Dr. [Andrian Marcus](http://www.utdallas.edu/~amarcus/){:target="_blank"}, and my B.Eng. and M.Eng. degrees in Systems Engineering and Computing from [Universidad Nacional de Colombia](https://bogota.unal.edu.co/){:target="_blank"} in Bogot&aacute;, Colombia.

***RECENT NEWS*** 

{% for item in site.data.news.main limit:10 %}
 {{ forloop.index }}. ({{ item.date }}) {{ item.text }}
{% endfor %}

<!-- ***IMPORTANT ADS*** 

**I am looking for motivated and skilled students (undergraduate and graduate) interested in software engineering (SE) research!**

**If you are not a student at W&M, consider applying to the [CS graduate program](https://www.wm.edu/as/computerscience/graduate/admission/index.php){:target="_blank"} (Fall deadline: March 1st/15th, Spring deadline: Oct. 1st).**

**Feel free to email me explaining your interest in my research & SE (attach your CV).** -->


