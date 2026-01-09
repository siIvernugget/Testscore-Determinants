# Econometrics Case Study: Determinants of Testscores
This repository contains an econometric analysis, as part of a university project, of factors influencing average testscores in public schools across the US, based on data from Stock and Watson's *Introduction to Econometrics*, available at https://www.princeton.edu/~mwatson/Stock-Watson_4E/Stock-Watson-Resources-4e.html. The analysis is performed using R and compiled into a LaTeX report using knitr.

## Overview
* **`testscore determinants.Rnw`**: The main source file. Contains LaTeX code for the report and R code for the analysis (Knits to PDF).
* **`CASchools_EE141_InSample.xlsx`**: The raw dataset used for the analysis.
* **`testscore determinants.pdf`**: The final compiled report.

## Prerequisites
To run the analysis and compile the PDF, make sure to install and run the following packages:

    ```r
    install.packages(c("tidyverse", "readxl", "knitr", "formatR", "tinytex"))
    ```

## How to Compile
To compile the PDF, follow these steps:
1.  Make sure your compiler is set to "knitr". To do that go to Tools-> Global Options-> Sweave-> Select: "Weave Rnw files using **knitr**" and "Typeset LaTeX into PDF using **pdfLaTeX**
1.  Open `birthweight.Rnw` in RStudio.
2.  Click the **Compile PDF** button.
