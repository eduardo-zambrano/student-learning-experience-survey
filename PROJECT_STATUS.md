# Project Status

*Last updated: February 26, 2026*

## Overview

In 2013, the Academic Senate adopted [AS-759-13](https://digitalcommons.calpoly.edu/senateresolutions/761/), establishing the current university-wide student evaluation questions. In 2025, ASI [Resolution #25-04](https://www.asi.calpoly.edu/wp-content/uploads/2025/05/Resolution-25-04_Resolution-on-Course-Evaluations.pdf) called for reform, and the Academic Senate established [the Ad Hoc Committee on Student Perception of Teaching Effectiveness](https://content-calpoly-edu.s3.amazonaws.com/academicsenate/1/images/Ad%20Hoc%20Committee%20on%20Teaching%20Effectiveness.pdf), charged with providing a revised policy and resolution to replace AS-759-13.

This repository supports the work of the Sub-Committee of that Ad Hoc Committee. The proposal — *The Student Learning Experience Survey: Rationale and Broad Principles of Design* — is published as a password-protected Quarto Book at:

**https://eduardo-zambrano.github.io/student-learning-experience-survey/**

## Repository Structure

| Directory | Contents |
|-----------|----------|
| `01_Proposed_Reforms/` | Earlier OCOB-level reform materials (policy analysis, recommendations, resolution, FAQ, presentation) |
| `02_Key_References/` | Research literature and legal references (SET bias, gender bias, Ryerson arbitration) |
| `03_Training_Template/` | Performance evaluation meeting agenda and training materials |
| `04_Presentation_for_Ad_Hoc_Committee/` | Quarto presentation for the Ad Hoc Committee |
| `05_New_Committee/` | **Active working directory** — Quarto Book source (see below) |

### `05_New_Committee/` — Quarto Book

| File | Role |
|------|------|
| `_quarto.yml` | Book configuration (title, chapters, HTML/PDF format options) |
| `index.qmd` | Preamble (authorship, disclaimer) |
| `Class_Climate_Subdimensions.qmd` | The Proposal (background, recommendations, rationale, five aspects of class climate, open-ended question) |
| `Appendices_Scoring_and_Reporting.qmd` | Appendix: scoring methodology, reporting guidelines, visualization guidelines |
| `visualization_examples.qmd` | Standalone draft mockups (not part of book) |
| `archive/` | Earlier Word drafts and Python scripts (gitignored from deploy) |
| `references/` | Reference PDFs (gitignored) |

### CI/CD

`.github/workflows/deploy.yml` renders the Quarto Book, encrypts the HTML with StaticCrypt, and deploys to GitHub Pages on every push to `main`.

## Current State of the Proposal

The proposal opens with a background section citing the three governing documents (AS-759-13, ASI Resolution #25-04, Ad Hoc Committee charge), then makes three recommendations:

### 1. Rename the instrument
From **Student Evaluation of Instruction/Faculty** to **Student Learning Experience Survey**. "Evaluation" mischaracterizes what the instrument does; students report experiences, not render verdicts.

### 2. Five aspects of class climate
The rationale section introduces the TEval framework's seven dimensions of teaching (Austin et al., 2025), applies three selection criteria (summative relevance, student competence, minimal bias), and identifies Dimension 3 — Class Climate — as the appropriate focus of the student survey. Class climate is then decomposed into five aspects:

- **Respect** — dignity and courtesy in interactions
- **Fairness** — equitable treatment and consistent standards
- **Participatory Climate** — conditions for active engagement
- **Approachability** — accessibility outside class
- **Inclusivity** — sense of belonging

### 3. Discontinue the open-ended question
Open-ended comments reintroduce the biases the structured items are designed to exclude. Unstructured feedback belongs in the formative component, shared only with the instructor.

## Appendix: Scoring and Reporting

The appendix specifies:

- **Scoring**: Ordered categorical data (Strongly Agree → Strongly Disagree) plus N/A. No numerical scoring. The instrument satisfies the CBA §15.17 definition of student course evaluations ("Scantron form, etc.").
- **Reporting**: Frequency distributions with raw counts (not percentages, not averages). Response rates reported as counts. No extrapolation. No cross-comparisons across instructors, courses, departments, or disciplines.
- **Visualization**: Vertical bar charts for single questions; diverging stacked bar charts for comparing multiple questions (Heiberger and Robbins, 2014).

## What Comes Next

Two forthcoming companion documents:

1. **Interpretation guidance** — a manual for evaluators on appropriate and inappropriate uses of the data.
2. **Implementation details** — timing, administration, and best practices for maximizing response rates.

## Key References

- Austin et al. (2025). *Transforming College Teaching Evaluation.* Harvard Education Press.
- Boring, Ottoboni, and Stark (2016). "Student Evaluations of Teaching (Mostly) Do Not Measure Teaching Effectiveness."
- Heiberger and Robbins (2014). "Design of Diverging Stacked Bar Charts for Likert Scales." *J. Stat. Softw.*
- Heffernan (2023). "Abusive Comments in Student Evaluations."
- Lang and Secic (2006). *How to Report Statistics in Medicine.*
- McCreary (2026). "A Practical Guide to Modern Teaching Evaluation." *Engaged Learning Collective.*
- Mitchell and Martin (2018). "Gender Bias in Student Evaluations."
- Moos (1979). *Evaluating Educational Environments.* Jossey-Bass.
- Fraser (1998). "Classroom Environment Instruments." *Learning Environments Research.*
- Ambrose et al. (2010). *How Learning Works.* Jossey-Bass.
- Stark (2016). "An Evaluation of Course Evaluations." Report to the TFA.
- Stark and Freishtat (2014). "An Evaluation of Course Evaluations."
- Stevens (1946). "On the Theory of Scales of Measurement."
- TEval Project (2025). NSF-funded initiative on teaching evaluation reform.
