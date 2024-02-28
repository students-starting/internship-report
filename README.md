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
quarto use students-starting/internship-report
```

This will install the extension and create an example `qmd` file that you can use as a starting place for your article.

Here is the source code for a minimal sample document: [template.qmd](template.qmd) and the related `pdf` file [template.pdf](template.pdf)