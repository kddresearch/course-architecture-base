<!--
---
yaml_schema_version: "2.2"
document_version: "1.0"
document_last_updated_date: "2026-10-12"
document_monotonicity: "REQUIRED"
routing_clearance: "PUBLIC - STUDENT FACING"
---
-->

<br>

<div align="center">
  <strong>🏫 Active Course Repositories:</strong> &nbsp;
  🏗️ <a href="https://github.com/kddresearch/course-architecture-base">Architecture Base</a> &nbsp;|&nbsp;
  🤖 CIS 530/730 &nbsp;|&nbsp;
  📊 <a href="https://github.com/kddresearch/cis531-731-2026_fall">CIS 531/731</a> &nbsp;|&nbsp;
  📈 CIS 732 &nbsp;|&nbsp;
  🎨 <a href="https://github.com/kddresearch/cis536-736-2026_fall">CIS 536/736</a> &nbsp;|&nbsp;
  👁️ CIS 798 X &nbsp;|&nbsp;
  🧠 CIS 830
</div>

<div align="center">
  <h1>📊 CIS 531/731 - Programming Techniques for Data Science and Analytics</h1>
  <p>
  <strong>Semester:</strong> Fall 2026 | <strong>Instructor:</strong> William H. Hsu<br>
  <strong>Status:</strong> ACTIVE | <strong>Canvas LMS:</strong> <a href="https://k-state.instructure.com/courses/201513">Closed SSO Portal</a>
  </p>
</div>

<hr>

<div align="center">
  <h2>📂 Directory: lectures/ (Course Lectures Index)</h2>
  <p>
  <strong>Status:</strong> ACTIVE | <strong>Maintainer:</strong> William H. Hsu
  </p>
</div>

<hr>

## 📖 Overview

This directory acts as the centralized repository for all lecture content, slide decks, and class notes. Each Markdown file corresponds directly to a scheduled class session. 

> **⚠️ Repository Routing Notice**
> Do not commit weekly lab datasets or runnable Jupyter Notebooks (`.ipynb`) directly to this root directory. All programmatic assets and data snippets associated with these lectures must be routed to their respective `module_XX/` subdirectories.

<hr>

## 🗂️ Lecture Schedule & File Paths

| Lecture | Date | Topic |
| :--- | :--- | :--- |
| [`Lec 00`](lecture-00.md) | Mon 24 Aug 2026 | Welcome & Course Overview |
| [`Lec 01`](lecture-01.md) | Wed 26 Aug 2026 | PySpark Intro: RDDs & DataFrames |
| [`Lec 02`](lecture-02.md) | Fri 28 Aug 2026 | Experiment Design & Reproducible Projects |
| [`Lec 03`](lecture-03.md) | Mon 31 Aug 2026 | RDD Transformations & Actions Lab |
| [`Lec 04`](lecture-04.md) | Wed 02 Sep 2026 | Wrap-Up |
| [`Lec 05`](lecture-05.md) | Fri 04 Sep 2026 | Tools: Cloud & Hosted Services |
| [`Lec 06`](lecture-06.md) | Wed 09 Sep 2026 | DevContainers & Docker |
| [`Lec 07`](lecture-07.md) | Fri 11 Sep 2026 | AI/LLM Tooling Overview; Wrap-Up |
| [`Lec 08`](lecture-08.md) | Mon 14 Sep 2026 | Obtain: ASR Stream Capture & VDB Corpus Acquisition |
| [`Lec 09`](lecture-09.md) | Wed 16 Sep 2026 | Whisper Architecture & Local Transcription |
| [`Lec 10`](lecture-10.md) | Fri 18 Sep 2026 | Corpus Acquisition Lab; Wrap-Up |
| [`Lec 11`](lecture-11.md) | Mon 21 Sep 2026 | Data Analytics Pipelines: Streaming & Data Lakes |
| [`Lec 12`](lecture-12.md) | Wed 23 Sep 2026 | Spark Structured Streaming |
| [`Lec 13`](lecture-13.md) | Fri 25 Sep 2026 | Streaming Lab; Wrap-Up |
| [`Lec 14`](lecture-14.md) | Mon 28 Sep 2026 | Scrub: Chunking & Embedding Generation |
| [`Lec 15`](lecture-15.md) | Wed 30 Sep 2026 | Semantic Search & VDB Schema Design |
| [`Lec 16`](lecture-16.md) | Fri 02 Oct 2026 | Embedding Lab / VDB Indexing; Wrap-Up |
| [`Lec 17`](lecture-17.md) | Mon 05 Oct 2026 | GenAI & LLMs: Candidates, Code, Classification |
| [`Lec 18`](lecture-18.md) | Wed 07 Oct 2026 | Few-Shot Trope/Genre Classification |
| [`Lec 19`](lecture-19.md) | Mon 12 Oct 2026 | Model Selection & Embedding-Backed Classification Lab |
| [`Lec 20`](lecture-20.md) | Wed 14 Oct 2026 | Trope/Genre Classification Workshop |
| [`Lec 21`](lecture-21.md) | Fri 16 Oct 2026 | Wrap-Up |
| [`Lec 22`](lecture-22.md) | Mon 19 Oct 2026 | Explore: Data Visualization & Dashboards |
| [`Lec 23`](lecture-23.md) | Wed 21 Oct 2026 | Embedding-Space Visualization (UMAP) |
| [`Lec 24`](lecture-24.md) | Fri 23 Oct 2026 | Generational Drift Dashboards Lab; Wrap-Up |
| [`Lec 25`](lecture-25.md) | Mon 26 Oct 2026 | Modeling: Retrieval-Augmented Classification |
| [`Lec 26`](lecture-26.md) | Wed 28 Oct 2026 | Feature Extraction Pipelines |
| [`Lec 27`](lecture-27.md) | Fri 30 Oct 2026 | Generational Convolution Models Lab; Wrap-Up |
| [`Lec 28`](lecture-28.md) | Mon 02 Nov 2026 | Evaluating Models: Inferential Statistics |
| [`Lec 29`](lecture-29.md) | Wed 04 Nov 2026 | ASR Evaluation Methodology & Gold-Standard Design |
| [`Lec 30`](lecture-30.md) | Fri 06 Nov 2026 | Gold-Standard Construction Lab; Wrap-Up |
| [`Lec 31`](lecture-31.md) | Mon 09 Nov 2026 | Interpret: Applying Models for Data Science |
| [`Lec 32`](lecture-32.md) | Wed 11 Nov 2026 | Model Metrics & Scoring |
| [`Lec 33`](lecture-33.md) | Fri 13 Nov 2026 | Interpretation Lab; Wrap-Up |
| [`Lec 34`](lecture-34.md) | Mon 16 Nov 2026 | Presenting Results: Data Storytelling |
| [`Lec 35`](lecture-35.md) | Wed 18 Nov 2026 | Documentation & Notebook Presentation Standards |
| [`Lec 36`](lecture-36.md) | Fri 20 Nov 2026 | Dashboard Design Workshop; Wrap-Up |
| [`Lec 37`](lecture-37.md) | Mon 30 Nov 2026 | PaaS/IaaS, MLOps/AIOps |
| [`Lec 38`](lecture-38.md) | Wed 02 Dec 2026 | MLflow Tracking & Deployment |
| [`Lec 39`](lecture-39.md) | Fri 04 Dec 2026 | Wrap-Up |
| [`Lec 40`](lecture-40.md) | Mon 07 Dec 2026 | Special Topics: Agentic AI Systems Overview |
| [`Lec 41`](lecture-41.md) | Wed 09 Dec 2026 | Special Topics: Frontier Directions in Responsive Analytics |
| [`Lec 42`](lecture-42.md) | Fri 11 Dec 2026 | Special Topics: Course Synthesis & Wrap-Up |

<br>
<hr>
<p align="center">
  <i>Maintained by the <a href="https://github.com/kddresearch">Knowledge Discovery in Databases (KDD) Lab</a> at Kansas State University.</i>
</p>
