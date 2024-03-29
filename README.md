
# Deploy a bookdown book with Github Action to RStudio connect service


This repo is just a demo on how to configure Github Action to publish to a Rstudio Connect based service (like bookdown.org, beta.rstudioconnect.com, ...)

All the interesting stuff from this repo are in `.github/workflows/`.  The book itself is from the https://github.com/rstudio/bookdown-demo

## Deployment methods tested

| Method                                                                             | Status                                                                                                                              | Docs                                                                                      | workflow |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------|
| Using `rsconnect` R :package:                                                      | ![book-deploy-build](https://github.com/cderv/deploy-bookdown-demo/workflows/book-deploy-build/badge.svg)                           | [Package website](https://rstudio.github.io/rsconnect/)                                   |          |
| Using `connectapi`, the R :package: for using the API                              | ![bookdown-deploy-r-api](https://github.com/cderv/deploy-bookdown-demo/workflows/bookdown-deploy-r-api/badge.svg)                   | [Package website](https://rstudio.github.io/connectapi/)                                  |          |
| Using `rsconnect-python`, the python API :package:                                 | ![book-deploy-python-api](https://github.com/cderv/deploy-bookdown-demo/workflows/book-deploy-python-api/badge.svg)                 | [Library website](https://pypi.org/project/rsconnect-python/#deploying-r-or-other-content) |          |
| Using `@rstudio/action/connect-publish`, the Github actions for publishing content | ![bookdown-deploy-connect-action](https://github.com/cderv/deploy-bookdown-demo/workflows/bookdown-deploy-connect-action/badge.svg) | [Action repo](https://github.com/rstudio/actions/tree/main/connect-publish)               |          |
