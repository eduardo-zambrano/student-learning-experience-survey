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
