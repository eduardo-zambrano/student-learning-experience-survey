# The Student Learning Experience Survey

**Rationale and Broad Principles of Design**

A proposal by the Sub-Committee of the Ad Hoc Committee on Student Perceptions of Teaching Effectiveness at Cal Poly.

> *This draft is a preliminary unofficial and incomplete working document, subject to additions and revisions.*

## About

This repository contains the source for a proposal to reform student evaluations of teaching at Cal Poly. The current university-wide evaluation questions were established by [AS-759-13](https://digitalcommons.calpoly.edu/senateresolutions/761/) (2013). In 2025, ASI [Resolution #25-04](https://www.asi.calpoly.edu/wp-content/uploads/2025/05/Resolution-25-04_Resolution-on-Course-Evaluations.pdf) called for reform, and the Academic Senate established [an Ad Hoc Committee](https://content-calpoly-edu.s3.amazonaws.com/academicsenate/1/images/Ad%20Hoc%20Committee%20on%20Teaching%20Effectiveness.pdf) charged with providing a revised policy and resolution to replace AS-759-13.

The proposal recommends:

1. **Renaming** the instrument from "Student Evaluation of Instruction/Faculty" to **Student Learning Experience Survey**
2. **Centering** the survey on five aspects of class climate — Respect, Fairness, Participatory Climate, Approachability, and Inclusivity — grounded in the TEval framework (Austin et al., 2025) and the broader literature on classroom climate
3. **Discontinuing** the open-ended question
4. **Reporting** results as frequency distributions of ordered categorical responses — no numerical averages, no percentages, no cross-comparisons

The proposal is grounded in the peer-reviewed literature on bias in student evaluations of teaching, including work by Stark, Boring, Ottoboni, Austin, Heiberger, and others.

## Current status

The Quarto Book has three chapters plus a preamble:

- **Preamble** (`index.qmd`) — contributors and status note
- **Chapter 1: The Proposal** (`Class_Climate_Subdimensions.qmd`) — rationale for the name change, the five aspects of the learning environment (Respect, Fairness, Participatory Climate, Approachability, Inclusivity), and removal of the open-ended question
- **Chapter 2: Scoring and Reporting** (`Appendices_Scoring_and_Reporting.qmd`) — frequency distributions, no averages, visualization guidelines
- **Chapter 3: Implementation Best Practices** (`Implementation_Best_Practices.qmd`) — covers timing, mode of administration, response-rate strategies, and anti-bias framing for the summative SLES under the 15-week semester calendar. Includes peer-institution comparison (SJSU, SDSU, UC Davis, UCSB, UCSD) and a recommended implementation model. Under active revision.

A companion document not yet part of the book:

- **Evaluator's manual** — in preparation; not yet drafted

Two standalone documents (not part of the book):

- `neutral_inventory/Implementation_Inventory.qmd` — comprehensive research inventory of implementation practices, organized by dimension, with full citations and a peer-institution comparison table. Serves as the evidence base behind Chapter 3.
- `formative/Formative_Check_In_Design.qmd` — design for a mid-semester formative check-in instrument (items, administration, closing-the-loop guidance). **Needs review** — first draft, not yet revised.

## Website

The rendered document is published at:

**https://eduardo-zambrano.github.io/student-learning-experience-survey/**

## Building locally

The document is a [Quarto Book](https://quarto.org/docs/books/). To render locally:

```bash
cd 05_New_Committee
quarto render
```

This produces HTML and PDF output in `05_New_Committee/_book/`. Requires [Quarto](https://quarto.org/) and R with the following packages: `knitr`, `kableExtra`, `ggplot2`, `ggthemes`, `dplyr`.
