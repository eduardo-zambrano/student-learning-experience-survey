# Project Status — SET Matters Repository

*Last updated: February 23, 2026*

## Overview

This repository supports the work of the Ad Hoc Committee on Student Perceptions of Teaching Effectiveness at Cal Poly. The committee is developing a proposal to reform the university's student evaluation of teaching instruments, grounded in the peer-reviewed literature on bias in student evaluations.

## Repository Structure

### `01_Proposed_Reforms/`
Earlier reform materials from the OCOB-level effort, including existing policy analysis, recommendations, a resolution for faculty vote, FAQ responses, and a presentation. These predate the current university-wide Ad Hoc Committee work.

### `02_Key_References/`
Research literature and legal references: summaries of SET bias research, gender bias in evaluations, the Stark expert report, and the Ryerson arbitration decision (2018 CanLII 58446).

### `03_Training_Template/`
Performance evaluation meeting agenda and training materials.

### `04_Presentation_for_Ad_Hoc_Committee/`
A Quarto-based presentation (`presentation.qmd`) prepared for the Ad Hoc Committee, with supporting styles and images.

### `05_New_Committee/` — **Active working directory**
This is where the current proposal is being developed. Key files:

| File | Description |
|------|-------------|
| `Class_Climate_Subdimensions.qmd` | **Primary proposal document** (Quarto source). Contains the full rationale for three recommendations: renaming the instrument, choosing five dimensions, and removing the open-ended question. Renders to both PDF and HTML. |
| `Class_Climate_Subdimensions.pdf` | Rendered PDF — static, formatted for print/distribution. |
| `Class_Climate_Subdimensions.html` | Rendered HTML — interactive, with collapsible callout blocks for supporting detail. |
| `Class_Climate_Subdimensions_files/` | Supporting files for the HTML output. |
| `Class_Climate_Subdimensions.zip` | Shareable bundle containing `.qmd`, `.pdf`, `.html`, and `_files/`. |
| `Class_Climate_Subdimensions.docx` | Earlier docx rendering (may be out of date relative to the QMD). |
| `mini-proposal.docx` | Working draft of the proposal in Word format. |
| `Two_Part_Plus_Checklists.docx` | Earlier proposal draft with the two-part survey structure and peer-review checklists. |
| `Two_Part_Plus_Checklists_JL.docx` | Version with Jean Lee's input. |
| `Two_Part_Survey_Instrument_Proposal.docx` | Original proposal document. |
| `Transforming_College_Teaching_Evaluation.pdf` | Reference: the TEval framework (pages 27–29 on the seven dimensions of teaching effectiveness). |
| `fix_styles.py` | Python script for applying style cleanup to docx files. |
| `generate_proposal.py` | Python script for generating proposal documents. |

## Current State of the Proposal

The proposal (`Class_Climate_Subdimensions.qmd`) makes three recommendations:

### 1. Rename the instrument
From **Student Evaluation of Instruction** / **Student Evaluation of Faculty** to **Student Learning Experience Survey**. The rationale: "evaluation" mischaracterizes what the instrument does; students report experiences, not render verdicts. The new name centers the student's experience and signals that the instrument is a survey, not an evaluation.

### 2. Five dimensions of class climate
The proposal identifies five subdimensions of the TEval framework's Class Climate dimension — the only dimension that simultaneously (a) carries a summative component, (b) students are qualified to assess, and (c) students can assess with minimal bias:

- **Respect** — dignity and courtesy in interactions
- **Fairness** — equitable treatment and consistent standards
- **Participatory Climate** — conditions for active engagement
- **Approachability** — accessibility outside class
- **Inclusivity** — sense of belonging

Each subdimension includes a description, a collapsible "How it differs" section, and candidate survey items (2–3 per dimension; committee selects one each).

### 3. Remove the open-ended question from the summative instrument
Open-ended comments reintroduce the biases the instrument is designed to exclude, resist standardized reporting, and contain disproportionately biased content toward women and marginalized academics. Unstructured feedback belongs in the formative component, which goes only to the instructor.

## What Comes Next

The proposal notes three forthcoming companion documents:

1. **Reporting and visualization guidelines** — how to present survey results (frequency distributions, no numerical averages, no cross-comparisons).
2. **Interpretation guidance** — a manual for evaluators on appropriate and inappropriate uses of the data.
3. **Implementation details** — timing, administration, and best practices for maximizing response rates.

## Key References Used in the Proposal

- Boring, Ottoboni, and Stark (2016). "Student Evaluations of Teaching (Mostly) Do Not Measure Teaching Effectiveness."
- Mitchell and Martin (2018). "Gender Bias in Student Evaluations."
- Storage et al. (2016). "The Frequency of 'Brilliant' and 'Genius' in Teaching Evaluations."
- Heffernan (2023). "Abusive Comments in Student Evaluations."
- Boysen et al. (2014). "The (Mis)interpretation of Teaching Evaluations."
- Linse (2017). "Interpreting and Using Student Ratings Data."
- Centra (1993). *Reflective Faculty Evaluation.*
- Berk (2005). "Survey of 12 Strategies to Measure Teaching Effectiveness."
- Benton and Young (2018). "Best Practices in the Evaluation of Teaching." IDEA Paper #69.
- Stark and Freishtat (2014). "An Evaluation of Course Evaluations."
