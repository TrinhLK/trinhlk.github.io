---
title: Checking the consistency of method names
date: 2018-10-01
category: blog
collaborators:
  - UT Dallas, USA
tags:
  - python
  - machine learning
image: images/blog/Jaist.jpg
---

Proposing an approach for Method Name Consistency Checking, which can: (1) Generate the candidate name for a given method; (2) Detect the consistency between the method's name and its implementation functionality.

To detect such inconsistency, it first generates the candidate name and then compares the current method name against that candidate. The more similar the more consistent they are. An inferred method name could be used for suggesting to replace the name of an inconsistent method, or to be used as the name of an un-named-yet method at the first place.