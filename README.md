---
layout: home
title: Home 
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

# DS-GA.1011 Natural Language Processing with Representation Learning, Fall 2023 
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About

How can we teach machines to understand human languages so that they can answer queries, summarize dense information, or hold a conversation with us? The primary goal of this course is to provide students with the principles and state-of-the-art tools needed to solve a variety of NLP problems. We will focus on three paradigms in the field of NLP: supervised learning, pretrain-then-finetune, and the most recent large language models, with a focus on representation learning techniques. Students are expected to read research papers and gain hands-on experience through coding assignments and course projects.

## Prerequisites

Students are expected to have a solid mathematics background and strong programming skills.

- Probability, statistics, linear algebra (DS-GA.1002, MATH-UA.140, MATH-UA.235)
- Algorithms and data structure (CSCI-UA.102)
- Basic knowledge in machine learning (DS-GA.1003, CSCI-UA.0473). We will not spend a significant amount of time on machine learning basics so some prior exposure to the supervised learning framework (e.g., loss functions, SGD) is expected.

## Logistics

- **Lectures**: Wed 12:00pm--1:40pm, 12 Waverly Pl G08 
  - Join on [Zoom](https://nyu.zoom.us/j/92498282358) using the NYU account
  - Zoom recordings can be found on Brightspace
- **Office hours**: We will have five office hours each week: one with the instructor (lecture or general questions) and one with each of the four section leaders (lecture or assignment questions). Details can be found on the [Staff page]({% link staff.md %}). You are also encouraged to ask questions on Campuswire, which will be answered by the TAs or your classmates.
- **Communication**: We will use [Campuswire](https://campuswire.com/c/GC1A61E84) as our main communication tool for announcements and answering questions related to the lectures, assignments, and projects. The registration link is available on [Brightspace](https://brightspace.nyu.edu/d2l/home/315303).

## Grading

- **Assignments (60%)**: There will be four assignments, each counting 15%.
- **Project (40%)**: You are required to complete a (group) project applying techniques learned in this course.

## Coursework
### Assignments
The assignments will contain both written problems and programming problems (in Python).

- **Late policy**: All assignments are due at noon 12:00pm (New York time) on the due date (which will be announced with the assignment). You have **8 late days** in total that can be distributed among the assignments. You may use a maximum of 7 late days for each assignment, i.e. we will not accept submissions a week after the deadline. Once you have used all 8 late days, each additional late day will incur a 5\% penalty on the assignment, e.g., if you are late for two days (beyond the legitimate 8 late days) and get 80 points on the assignment, you final points will be 80-80*(5\% + 5\%)=72.
- **Collaboration policy**: You may discuss problems with your classmates. However, you must write up the homework solutions and the code from scratch, without referring to notes from your joint session. In your solution to each problem, you must write down the names of any person with whom you discussed the problem; this will not affect your grade.
- **Submission**: Assignments are submitted through Gradescope. At the beginning of the semester, you will be added to the Gradescope roster through Brightspace. Please do not register on Gradescope separately or change your email; this will cause the rosters will be out-of-sync. 
- **Grading**: We aim to release grades within two weeks of the submission date. Once the grades are released, you will have one week to submit any regrading requests.

### Project
The project is an important component of this course.
It allows you to apply what you have learned to a real problem. You are asked to complete the project in a group of **1 to 5** students. We strongly recommend you do projects in a team. Larger groups are expected to show more efforts. 

- **Topics**: You can choose any topics related to NLP. Take a look at the [ACL proceedings](https://www.aclweb.org/anthology/) for inspiration. Here are some general directions:
  - A new algorithm or model for important problems, e.g., identifying factual errors from LLM's outputs 
  - An application of an existing technology, e.g., use NLP models for healthcare problems 
  - Analysis of a dataset, a model, or an approach, e.g., failure modes of chain-of-thought prompting
  - Replication of a published result (see the [Reproducibility Challenge](https://arxiv.org/pdf/2003.12206.pdf))

- **Deliverables**:
  - Proposal (5%): You are required to submit a two-page proposal that describes the team and your project plan.
  - Presentation (10%): Each group will give a short presentation (3 minutes) of their work followed by Q&A (1 minutes) in the last week.
  - Report (25%): The final report is due on **Dec 15**. Each group should submit a report in .pdf in the ACL [templates](https://2023.aclweb.org/calls/style_and_formatting/).
