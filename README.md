# CSAM-Sandbox

Example repository to demonstrate the creation of CSAS documents.

A sample report is provided in **RV-SciResponse-EN/**. The rendered PDF version is located at **RV-SciResponse-EN/\_book/\_main.pdf**.

# Intsallation

To render the report locally, follow the csasdown installation instructions: <https://github.com/pbs-assess/csasdown>. Once the necessary dependencies are installed (primarily latex and pandoc), the installation process is:

``` r
install.packages("remotes")
remotes::install_github("pbs-assess/csasdown")
```

With csasdown installed you should be able to knit **RV-SciResponse-EN/index.Rmd** and sucessfully regenerate the **RV-SciResponse-EN/book/\_main.pdf***.*
