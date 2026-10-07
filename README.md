<!--
yaml_schema_version: "2.2"
document_version: "2.4"
document_last_updated_date: "2026-10-06"
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

---

<h1 align="center">🗃️ Template Repository for KDD Lab Courses 📚</h1>

---

<div align="center">
 <h1>🧪 {{COURSE_NUMBER}} - {{COURSE_TITLE}}</h1>
 <p>
 <strong>Semester:</strong> {{SEMESTER}} | <strong>Principal Investigator / Instructor:</strong> William H. Hsu, Ph.D.<br>
 <strong>Status:</strong> {{ACTIVE / ARCHIVED}} | <strong>Canvas LMS:</strong> <a href="{{CANVAS_URL}}">Closed SSO Portal</a>
 </p>
</div>

<hr>

## 📖 Overview

{{COURSE_DESCRIPTION}}

> **⚠️ Single Source of Truth (SSOT) Notice**
> This repository is the designated SSOT for all public-facing course materials, assignments, and infrastructure. While grades and closed discussions occur in the Canvas SSO environment, all operational state, Machine Problems (MPs), codebases, and structural rubrics MUST be committed here before being mirrored. A non-paywalled HTML mirror of Canvas content is derived from this repository.

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `.github/` | CI/CD workflows and sync configurations (e.g., `sync_architecture_template.yml`). |
| `admin/` | Course policies and syllabus resources. |
| `assignments/` | Homework, machine problems, project milestones, and labs. |
| `exams_quizzes/` | Quizzes, exams, and other assessments  **that are *taken*, not submitted***. |
| `lectures/` | Core lecture materials and related assets. |
| `modules/` | Weekly/topic-based module directories (`module_00` to `module_13`). |
| `phases/` | High-level course progression phase wrappers (`phase_01` to `phase_05`). |
| `platforms/` | Platform-specific configurations and assets (Canvas, Gemini, Piazza). |
| `reading_materials/` | Assigned papers, texts, and supplementary reading. |
| `slides/` | Slide decks and archived presentations. |
| `term_project/` | Rubrics, sprint specs, and `docker` compute configs for the term project. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* {{DEPENDENCY_1}}
* {{DEPENDENCY_2}}

**2. Initialization**
```bash
git clone {{REPO_URL}}
cd {{REPO_NAME}}
# Setup commands
```

## 📂 Repository Structure (Full Tree)

<details>
<summary><b>Click to expand: Course Repository Template Directory Tree</b></summary>

```
Folder PATH listing for volume Windows
Volume serial number is 60E2-4FEF
C:.
|   .gitignore
|   LICENSE
|   README.md
|   structure_dump.txt
|   
+---.github
|   \---workflows
|           sync_architecture_template.yml
|           
+---admin
|   +---policies
|   |       .gitkeep
|   |       
|   \---syllabus
|           .gitkeep
|           
+---assignments
|   |   .gitkeep
|   |   
|   +---homework
|   |       .gitkeep
|   |       
|   +---machine_problems
|   |       .gitkeep
|   |       
|   \---project_sprints
|           .gitkeep
|           
+---lectures
|       .gitkeep
|       
+---modules
|   |   module_template.md
|   |   
|   +---module_00
|   |       .gitkeep
|   |       
|   +---module_01
|   |       .gitkeep
|   |       
|   +---module_02
|   |       .gitkeep
|   |       
|   +---module_03
|   |       .gitkeep
|   |       
|   +---module_04
|   |       .gitkeep
|   |       
|   +---module_05
|   |       .gitkeep
|   |       
|   +---module_06
|   |       .gitkeep
|   |       
|   +---module_07
|   |       .gitkeep
|   |       
|   +---module_08
|   |       .gitkeep
|   |       
|   +---module_09
|   |       .gitkeep
|   |       
|   +---module_10
|   |       .gitkeep
|   |       
|   +---module_11
|   |       .gitkeep
|   |       
|   +---module_12
|   |       .gitkeep
|   |       
|   \---module_13
|           .gitkeep
|           
+---phases
|   +---phase_01
|   |       .gitkeep
|   |       
|   +---phase_02
|   |       .gitkeep
|   |       
|   +---phase_03
|   |       .gitkeep
|   |       
|   +---phase_04
|   |       .gitkeep
|   |       
|   \---phase_05
|           .gitkeep
|           
+---platforms
|   |   .gitkeep
|   |   
|   +---canvas
|   |       .gitkeep
|   |       
|   +---gemini
|   |       .gitkeep
|   |       
|   +---github
|   |       github_intro.md
|   |       
|   +---moodle
|   |       .gitkeep
|   |       
|   \---piazza
|           .gitkeep
|           
+---reading_materials
|       .gitkeep
|       
+---slides
|   |   README.md
|   |   
|   \---archive
|           .gitkeep
|           
\---term_project
    |   .gitkeep
    |   
    \---docker
            .gitkeep
```
</details>
