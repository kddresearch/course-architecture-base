<!--
---
yaml_schema_version: "2.2"
document_version: "1.0"
document_last_updated_date: "2026-11-27"
document_last_updated_time: "00:01:00 CST"
document_monotonicity: "REQUIRED"
routing_clearance: "PUBLIC - STUDENT FACING"
template_metadata:
  template_id: "syllabus_README_template"
  description: "Generic course syllabus and policies directory README template"
  target_filename: "README.md"
  hydration_instructions:
    step_1: "Replace all {{PLACEHOLDER}} tokens with course-specific metadata, document titles, and descriptions."
    step_2: "Add, remove, or reorder document rows in the Directory Structure table to match the course's syllabus and policy documents."
    step_3: "Ensure relative links to Markdown (.md) and HTML (.html) files match the hydrated filenames in admin/syllabus/."
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
 <h1>{{COURSE_BADGE_EMOJI}} {{COURSE_NUMBER}} - {{COURSE_TITLE}}</h1>
 <p>
 <strong>Semester:</strong> {{SEMESTER}} | <strong>Instructor:</strong> {{INSTRUCTOR_NAME}}<br>
 <strong>Status:</strong> {{COURSE_STATUS}} | <strong>Canvas LMS:</strong> <a href="{{CANVAS_URL}}">Closed SSO Portal</a>
 </p>
</div>

<hr>

<div align="center">
 <h2>📂 Directory: admin/syllabus</h2>
 <p>
 <strong>Status:</strong> {{DIRECTORY_STATUS}} | <strong>Maintainer:</strong> {{MAINTAINER_NAME}}
 </p>
</div>

<hr>

## 📖 Overview

This directory contains the canonical Single Source of Truth (SSOT) documents for the {{COURSE_NUMBER}} course structure. It holds the core academic contracts, including the master syllabus, chronological schedule, environment setup requirements, and the frameworks governing course projects and evaluations. All Canvas pages in the "Syllabus & Policies" module are generated from or mirrored with the Markdown and HTML artifacts housed here.

> **⚠️ Sub-Directory Routing Notice**
> This directory serves a specific operational function. Ensure that artifacts committed here are strictly syllabus-level policies or structural guides. Grading rubrics specific to individual assignments belong in the `assignments/` directory.

<hr>

## 🗂️ Directory Structure

| Document | Formats | Description |
| :--- | :--- | :--- |
| {{DOC_01_TITLE}} | [Markdown]({{DOC_01_SLUG}}.md) · [HTML]({{DOC_01_SLUG}}.html) | {{DOC_01_DESC}} |
| {{DOC_02_TITLE}} | [Markdown]({{DOC_02_SLUG}}.md) · [HTML]({{DOC_02_SLUG}}.html) | {{DOC_02_DESC}} |
| {{DOC_03_TITLE}} | [Markdown]({{DOC_03_SLUG}}.md) · [HTML]({{DOC_03_SLUG}}.html) | {{DOC_03_DESC}} |
| {{DOC_04_TITLE}} | [Markdown]({{DOC_04_SLUG}}.md) · [HTML]({{DOC_04_SLUG}}.html) | {{DOC_04_DESC}} |
| {{DOC_05_TITLE}} | [Markdown]({{DOC_05_SLUG}}.md) · [HTML]({{DOC_05_SLUG}}.html) | {{DOC_05_DESC}} |
| {{DOC_06_TITLE}} | [Markdown]({{DOC_06_SLUG}}.md) · [HTML]({{DOC_06_SLUG}}.html) | {{DOC_06_DESC}} |
| {{DOC_07_TITLE}} | [Markdown]({{DOC_07_SLUG}}.md) · [HTML]({{DOC_07_SLUG}}.html) | {{DOC_07_DESC}} |
| {{DOC_08_TITLE}} | [Markdown]({{DOC_08_SLUG}}.md) · [HTML]({{DOC_08_SLUG}}.html) | {{DOC_08_DESC}} |
| Directory Index | [Markdown](README.md) | This file. |

<hr>

## 🦅 Standard Operating Procedures (SOPs)

All personnel interacting with this directory must adhere to the following protocols:

* **Protocol 1 (SSOT Paramountcy):** Do not update policies directly in Canvas HTML. The Markdown files in this directory must be updated first, and the HTML mirrored from them.
* **Protocol 2 (Strict Numbering):** Files in this directory use sequential numbering (`01_`, `02_`) to enforce pedagogical reading order. Do not break the prefix sequence when adding new structural documents.

<br>
<hr>
<p align="center">
 <i>Maintained by the <a href="https://github.com/kddresearch">Knowledge Discovery in Databases (KDD) Lab</a> at Kansas State University.</i>
</p>
