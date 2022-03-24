# CSAM-Sandbox

Example repository to demonstrate the creation of CSAS documents.

A sample report is provided in **RV-SciResponse-EN/**. The rendered PDF version is located at **RV-SciResponse-EN/\_book/\_main.pdf**.

# Installation

To render the report locally, follow the csasdown installation instructions: <https://github.com/pbs-assess/csasdown>. Once the necessary dependencies are installed (primarily latex and pandoc), the installation process is:

``` r
install.packages("remotes")
remotes::install_github("pbs-assess/csasdown")
```

With csasdown installed you should be able to knit **RV-SciResponse-EN/index.Rmd** and sucessfully regenerate the **RV-SciResponse-EN/book/\_main.pdf***.*
=======
Collection of repositories to explore the creation of CSAS documents

This documents relies on the R package csasdown - which facilitates generating Canadian Science Advisory Secretariat (CSAS) documents in PDF or Word format using R Markdown and bookdown. Pandoc and LaTeX are required. More information is available here: https://github.com/pbs-assess/csasdown  and a typical Latex setup is using tinytex installed through R on Windows. A detailed description of the installation process used is available here: https://github.com/pbs-assess/csasdown/wiki/Latex-Installation-for-csasdown

