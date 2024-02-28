# Internship Report

This simple Quarto template is used to create an internship report for students at the University of Padova. Before using the template you need to:

- Install R and RStudio
- Install Quarto (see [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/))

After installing R and Quarto, you need to install `tinytex` (see [https://quarto.org/docs/output-formats/pdf-engine.html](https://quarto.org/docs/output-formats/pdf-engine.html)) to compile documents in `pdf`. You can install it using from the command line:

```bash
quarto install tinytex
```

## Installing

To use the template you can move in a folder where you want to create the document and using the command line:

```bash
quarto use template students-starting/internship-report
```

This will install the extension and create an example `qmd` file that you can use as a starting place for your article.

## R Project

I suggest you to create an R Project from R Studio within a folder for your internship project (see [https://support.posit.co/hc/en-us/articles/200526207-Using-RStudio-Projects](https://support.posit.co/hc/en-us/articles/200526207-Using-RStudio-Projects)). Then you run the `quarto use template ...` command within this folder. In this way you have an R Project where you can work with R if necessary and then your template to create the report.
