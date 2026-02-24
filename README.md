# The Student Learning Experience Survey

**Rationale and Broad Principles of Design**

A proposal by the Sub-Committee of the Ad Hoc Committee on Student Perceptions of Teaching Effectiveness at Cal Poly.

> *This draft is a preliminary unofficial and incomplete working document, subject to additions and revisions.*

## About

This repository contains the source for a proposal to reform student evaluations of teaching at Cal Poly's Orfalea College of Business. The proposal recommends:

1. **Renaming** the instrument from "Student Evaluation of Instruction/Faculty" to **Student Learning Experience Survey**
2. **Centering** the survey on five dimensions of class climate that students are qualified to report on: Respect, Fairness, Participatory Climate, Approachability, and Inclusivity
3. **Removing** the open-ended question from the summative component
4. **Reporting** results as frequency distributions of ordered categorical responses — no numerical averages, no percentages, no cross-comparisons

The proposal is grounded in the peer-reviewed literature on bias in student evaluations of teaching, including work by Stark, Boring, Ottoboni, Heiberger, and others.

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
