<!--
---
yaml_schema_version: "2.2"
document_version: "1.0"
document_last_updated_date: "{{YYYY-MM-DD}}"
document_monotonicity: "REQUIRED"
routing_clearance: "PUBLIC - STUDENT FACING"
---
-->

<br>

<div align="center">
  <strong>🏫 Active Course Repositories:</strong> &nbsp;
  🏗️ <a href="https://github.com/kddresearch/course-architecture-base">Architecture Base</a> &nbsp;|&nbsp;
  🤖 CIS 530/730 &nbsp;|&nbsp;
  📊 CIS 531/731 &nbsp;|&nbsp;
  📈 CIS 732 &nbsp;|&nbsp;
  🎨 CIS 536/736 &nbsp;|&nbsp;
  👁️ CIS 798 X &nbsp;|&nbsp;
  🧠 CIS 830
</div>

<div align="center">
  <h1>{{EMOJI}} {{COURSE_ID}} - {{COURSE_TITLE}}</h1>
  <p>
  <strong>Semester:</strong> {{SEMESTER}} | <strong>Instructor:</strong> William H. Hsu<br>
  <strong>Status:</strong> {{ACTIVE / ARCHIVED}} | <strong>Canvas LMS:</strong> <a href="{{CANVAS_URL}}">Closed SSO Portal</a>
  </p>
</div>

<hr>

<div align="center">
  <h2>📂 Directory: lectures/ (Course Lectures Index)</h2>
  <p>
  <strong>Status:</strong> {{ACTIVE / ARCHIVED}} | <strong>Maintainer:</strong> {{MAINTAINER_NAME}}
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
| [`Lec 00`](lecture-00.md) | {{LEC_00_DATE}} | {{LEC_00_TITLE}} |
| [`Lec 01`](lecture-01.md) | {{LEC_01_DATE}} | {{LEC_01_TITLE}} |
| [`Lec 02`](lecture-02.md) | {{LEC_02_DATE}} | {{LEC_02_TITLE}} |
| [`Lec 03`](lecture-03.md) | {{LEC_03_DATE}} | {{LEC_03_TITLE}} |
| [`Lec 04`](lecture-04.md) | {{LEC_04_DATE}} | {{LEC_04_TITLE}} |
| [`Lec 05`](lecture-05.md) | {{LEC_05_DATE}} | {{LEC_05_TITLE}} |
<!-- REPEAT ROW BLOCK FOR REMAINING LECTURES (06 - N) AS DEFINED BY COURSE SCHEDULE YAML -->

<br>
<hr>
<p align="center">
  <i>Maintained by the <a href="https://github.com/kddresearch">Knowledge Discovery in Databases (KDD) Lab</a> at Kansas State University.</i>
</p>
