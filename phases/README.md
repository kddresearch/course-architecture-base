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
 <h2>📂 Directory: phases/ (Course Progression Index)</h2>
 <p>
 <strong>Status:</strong> {{ACTIVE / ARCHIVED}} | <strong>Maintainer:</strong> William H. Hsu
 </p>
</div>

<hr>

## 📖 Overview

This directory acts as the master index for the high-level course progression. **Phases** are conceptual, chronological wrappers that group multiple weekly modules together based on major pedagogical milestones or methodological pillars (e.g., Foundations, Obtain/Scrub, Explore/Model, Evaluate). 

> **⚠️ Parent Directory Routing Notice**
> This directory is strictly for structural routing. All actual course content, scripts, and assignment assets must be placed inside the granular `module_XX/` subdirectories located in the `modules/` repository root.

<hr>

## 🗂️ Phase Directory Structure

| Phase Directory | Pedagogical Objective |
| :--- | :--- |
| [`phase_01/`](phase_01/) | **{{PHASE_1_TITLE}}:** {{PHASE_1_DESCRIPTION}} |
| [`phase_02/`](phase_02/) | **{{PHASE_2_TITLE}}:** {{PHASE_2_DESCRIPTION}} |
| [`phase_03/`](phase_03/) | **{{PHASE_3_TITLE}}:** {{PHASE_3_DESCRIPTION}} |
| [`phase_04/`](phase_04/) | **{{PHASE_4_TITLE}}:** {{PHASE_4_DESCRIPTION}} |
| [`phase_05/`](phase_05/) | **{{PHASE_5_TITLE}}:** {{PHASE_5_DESCRIPTION}} |

<br>
<hr>
<p align="center">
 <i>Maintained by the <a href="https://github.com/kddresearch">Knowledge Discovery in Databases (KDD) Lab</a> at Kansas State University.</i>
</p>
