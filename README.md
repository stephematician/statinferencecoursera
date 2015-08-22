## Course Project for Statistical Inference

Generate the PDF output via the command

```r
library(rmarkdown)
setwd('directory_of_file')
render('CP1_exponential_rvs_and_CLT.Rmd', output_format="pdf_document")
render('CP1_toothgrowth_test.Rmd', output_format="pdf_document")
```