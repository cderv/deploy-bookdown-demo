
# Deploy a bookdown book with Github Action to RStudio connect (bookdown.org)

This book is from the https://github.com/rstudio/bookdown-demo

This repo is just a demo on how to configure Github Action to publish to a Rstudio Connect based service (like bookdown.org)

## Deployment method tested

| Method                                                                             | Status                                                                                                                              | Docs | workflow |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|------|----------|
| Using `rsconnect` R :package                                                       | ![book-deploy-build](https://github.com/cderv/deploy-bookdown-demo/workflows/book-deploy-build/badge.svg)                           |      |          |
| Using `connectapi`, the R :package: for using the API                              | ![bookdown-deploy-r-api](https://github.com/cderv/deploy-bookdown-demo/workflows/bookdown-deploy-r-api/badge.svg)                   |      |          |
| Using `rsconnect-python`, the python API :package:                                 | ![book-deploy-python-api](https://github.com/cderv/deploy-bookdown-demo/workflows/book-deploy-python-api/badge.svg)                 |      |          |
| Using `@rstudio/action/connect-publish`, the Github actions for publishing content | ![bookdown-deploy-connect-action](https://github.com/cderv/deploy-bookdown-demo/workflows/bookdown-deploy-connect-action/badge.svg) |      |          |

