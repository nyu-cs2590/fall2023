---
layout: page
title: About
description: >-
    Course policies and information.
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
- **Sections**: Mon 10:15am-11:05am, 19 University Place, Room 102
  - Join on [Zoom](https://nyu.zoom.us/j/94436115847) using the NYU account
  - Zoom recordings can be found on Brightspace
- **Office hours**: We will have five office hours each week: one with the instructor (lecture or general questions) and one with each of the four section leaders (lecture or assignment questions). Details can be found on the [Staff page]({% link staff.md %}). You are also encouraged to ask questions on Campuswire, which will be answered by the TAs or your classmates.
- **Communication**: We will use [Campuswire](https://campuswire.com/c/GC1A61E84) as our main communication tool for announcements and answering questions related to the lectures, assignments, and projects. The registration link is available on [Brightspace](https://brightspace.nyu.edu/d2l/home/315303).

## Grading

- **Assignments (60%)**: There will be four assignments, each counting 15%.
- **Project (40%)**: You are required to complete a (group) project applying techniques learned in this course. All group members will receive the same grade.
  - **Proposal (5%)**
  - **Presentation (10%)**: We will grade it based on your 3-minute presentation and 2-minute Q&A during the class. 
    - Clarity (6%): Is each component of the project clearly communicated?
      - Problem statement (2%)
      - Approach (2%)
      - Evaluation and results (2%)
    - Style (2%): Are the text, figures, tables legible and the speaker articulated?
    - Q&A (2%): Are the questions answered satisfactorily?
  - **Report (25%)**:
    - Format (2%): Is it following the given template and within the page limit?
    - Clarity (9%): Is each component described precisely and concisely?
      - Problem (3%)
      - Approach (3%)
      - Evaluation and results (3%)
    - Literature survey (3%): Is the relevant literature covered sufficiently?
    - Evaluation (4%): Is the evaluation justified and sufficient?
    - Contribution (3%): Does the project make a respectable contribution?
    - Effort (4%): Does the project demonstrate typical effort expected from the respective group size?

## Coursework
### Assignments
The assignments will contain both written problems and programming problems (in Python).

- **Late policy**: All assignments are due at noon 12:00pm (New York time) on the due date (which will be announced with the assignment). You have **8 late days** in total that can be distributed among the assignments. You may use a maximum of 7 late days for each assignment, i.e. we will not accept submissions a week after the deadline. Once you have used all 8 late days, each additional late day will incur a 5% penalty on the assignment, e.g., if you are late for two days (beyond the legitimate 8 late days) and get 80 points on the assignment, you final points will be 80-80*(5% + 5%)=72.
- **Collaboration policy**: You may discuss problems with your classmates. However, you must write up the homework solutions and the code from scratch, without referring to notes from your joint session. In the submission, you must write down the names of any person with whom you discussed the problem; this will not affect your grade.
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
  - Presentation (10%): Each group will give a short presentation (3 minutes) of their work followed by Q&A (2 minutes) in the last week.
  - Report (25%): The final report is due on **Dec 15**. 

## Academic integrity
Work you submit should be your own. Please consult the CAS academic integrity policy for more information: http://cas.nyu.edu/page/academicintegrity.  Penalties for violations of academic integrity may include failure of the course, suspension from the University, or even expulsion.

## AI policy
For the assignments and projects, you are free to use any AI-powered tools including ChatGPT. However, you must declare how you used these tools. This will not affect your grades.
