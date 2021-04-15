# Estimating The Effect of Public Postings of Norms in Subreddits: Data and Code
This folder includes data and code associated with the experiment pre-registered on the Open Science Framework on August 25, 2016: [Estimating the Effect of Public Postings of Norms in Subreddits: Pre-Analysis Plan](https://osf.io/jhkcf/). The files in this folder include:

* `science_analysis_final_paper-08.2018.R`: the full R code from the paper
* `r_science_experiment_1_posts.09.26.2016.csv` all posts in the experiment, including randomization blocks removed due to software errors

This paper has been submitted by PNAS:
* So, Wonyoung (2021) [Tenant screening services reinforce landlords' automation bias and blanket rejection behavior]. Proceedings of the National Academy of Sciences Apr 2021. Under Review.

# R Library versions used in this analysis
The following is output from the sessionInfo() command in R from the R version and libraries that were used to generate results:

```
R version 4.0.2 (2020-06-22)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS  10.16

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.0/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] plyr_1.8.6      jsonlite_1.7.0  httr_1.4.2      stargazer_5.2.2
 [5] rdrobust_0.99.9 forcats_0.5.0   stringr_1.4.0   dplyr_1.0.5    
 [9] purrr_0.3.4     readr_1.3.1     tidyr_1.1.3     tibble_3.0.3   
[13] ggplot2_3.3.2   tidyverse_1.3.0 foreign_0.8-80 

loaded via a namespace (and not attached):
 [1] tidyselect_1.1.0 xfun_0.16        haven_2.3.1      colorspace_1.4-1
 [5] vctrs_0.3.7      generics_0.0.2   htmltools_0.5.0  yaml_2.2.1      
 [9] blob_1.2.1       rlang_0.4.10     pillar_1.4.6     glue_1.4.2      
[13] withr_2.2.0      DBI_1.1.0        dbplyr_1.4.4     modelr_0.1.8    
[17] readxl_1.3.1     lifecycle_1.0.0  munsell_0.5.0    gtable_0.3.0    
[21] cellranger_1.1.0 rvest_0.3.6      evaluate_0.14    knitr_1.29      
[25] fansi_0.4.1      broom_0.7.1      Rcpp_1.0.5       scales_1.1.1    
[29] backports_1.1.9  fs_1.5.0         hms_0.5.3        digest_0.6.25   
[33] stringi_1.4.6    grid_4.0.2       cli_2.0.2        tools_4.0.2     
[37] magrittr_1.5     crayon_1.3.4     pkgconfig_2.0.3  ellipsis_0.3.1  
[41] xml2_1.3.2       reprex_0.3.0     lubridate_1.7.9  assertthat_0.2.1
[45] rmarkdown_2.3    rstudioapi_0.11  R6_2.4.1         compiler_4.0.2 
```
