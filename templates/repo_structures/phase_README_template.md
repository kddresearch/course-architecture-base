<!--
---
yaml_schema_version: "2.2"
document_version: "2.0"
document_last_updated_date: "2026-11-05"
document_monotonicity: "REQUIRED"
routing_clearance: "INTERNAL - RESTRICTED TO COURSE MAINTAINERS"
template_metadata:
  template_id: "phase_README_template"
  description: "Specialized phase directory README template for CIS 531/731 Fall 2026"
  target_filename: "README.md"
  hydration_instructions:
    step_1: "Replace all template variables enclosed in double curly braces (e.g., {{ PHASE_NUMBER }}) with actual phase metadata."
    step_2: "Configure phase_metadata block attributes (phase_number, phase_identifier, color_scheme, hex_code, badge_pill) to match the target phase."
    step_3: "Ensure relative paths and module table rows match the included modules for the phase."
phase_metadata:
  phase_number: {{ PHASE_NUMBER }}
  phase_identifier: "{{ PHASE_IDENTIFIER }}"
  color_scheme: "{{ COLOR_SCHEME }}"
  hex_code: "{{ HEX_CODE }}"
  badge_pill: "{{ BADGE_PILL }}"
---
-->

**🏫 Active Course Repositories:** 🏗️ [Architecture Base](https://github.com/kddresearch/course-architecture-base) &nbsp;|&nbsp; 🤖 CIS 530/730 &nbsp;|&nbsp; 📊 [CIS 531/731](https://github.com/kddresearch/cis531-731-2026_fall) &nbsp;|&nbsp; 📈 CIS 732 &nbsp;|&nbsp; 🎨 [CIS 536/736](https://github.com/kddresearch/cis536-736-2026_fall) &nbsp;|&nbsp; 👁️ CIS 798 X &nbsp;|&nbsp; 🧠 CIS 830

# 📊 CIS 531/731 - Programming Techniques for Data Science and Analytics

**Semester:** Fall 2026 | **Instructor:** William H. Hsu  
**Status:** ACTIVE | **Canvas LMS:** [Closed SSO Portal](https://k-state.instructure.com/courses/201513)

---

## {{ BADGE_PILL }} Phase {{ PHASE_NUMBER }}: {{ PHASE_TITLE }}

**Status:** ACTIVE | **Maintainer:** Course Maintainers / KDD Lab

---

## 📖 Overview

This directory defines **Phase {{ PHASE_NUMBER }}** of the course progression. For the complete canonical specification, detailed lecture objectives, and the unified chronological reading schedule, see [Phase {{ PHASE_NUMBER }} Specification (`phase_{{ PHASE_NUMBER_PADDED }}.md`)](./phase_{{ PHASE_NUMBER_PADDED }}.md) and [Assigned Reading(s)](../../reading_materials/readings_by_lecture.md).

Phases act as high-level chronological and thematic wrappers that group multiple weekly modules together based on major pedagogical milestones (e.g., OSEMN framework transitions). This phase specifically focuses on {{ PHASE_SUMMARY }}.

> **⚠️ Phase Routing Notice**
> This directory acts primarily as an organizational wrapper. Ensure that granular lecture assets, code snippets, and weekly materials are placed within their respective `module_XX/` subdirectories, rather than loosely at the root of the phase directory.

---

## 🗂️ Phase Structure (Included Modules)

| Module Directory | Topic / Description | Lectures | Date Range | Assigned Reading |
| :--- | :--- | :--- | :--- | :--- |
| [`module_{{ MOD_1_NUM }}/`](../../modules/module_{{ MOD_1_NUM }}/) | **[Module {{ MOD_1_NUM }}: {{ MOD_1_TITLE }}](../../modules/module_{{ MOD_1_NUM }}/module_{{ MOD_1_NUM }}.md):** {{ MOD_1_DESC }} | Lectures {{ MOD_1_LECTURES }} | {{ MOD_1_DATES }} | [Assigned Reading(s)](../../reading_materials/readings_by_lecture.md) |
| [`module_{{ MOD_2_NUM }}/`](../../modules/module_{{ MOD_2_NUM }}/) | **[Module {{ MOD_2_NUM }}: {{ MOD_2_TITLE }}](../../modules/module_{{ MOD_2_NUM }}/module_{{ MOD_2_NUM }}.md):** {{ MOD_2_DESC }} | Lectures {{ MOD_2_LECTURES }} | {{ MOD_2_DATES }} | [Assigned Reading(s)](../../reading_materials/readings_by_lecture.md) |

---

## 🦅 Standard Operating Procedures (SOPs)

All instructional staff interacting with this phase directory must adhere to the following protocols:

* **Protocol 1 (Phase Cohesion):** Ensure all modules contained within this phase cleanly map to the overarching phase objective defined in the syllabus taxonomy.
* **Protocol 2 (Navigation):** Maintain cross-links in the module READMEs pointing back to this Phase root to preserve GitOps navigability.
* **Protocol 3 (Milestone Anchoring):** Ensure the terminal module of this phase explicitly prepares the student for the associated major assignment/milestone.

---

*Maintained by the [Knowledge Discovery in Databases (KDD) Lab](https://github.com/kddresearch) at Kansas State University.*
