#Sentiment Analyis of Dineout Vancouver 2017 Tweets

This repository contains a jupyter notebook, an R Markdown file and data used in the creation of this post on my blog: [https://kitsonswann.github.io/DineoutSentiment.html](https://kitsonswann.github.io/DineoutSentiment.html)

**Instructions:**

To run the script that grabs the tweets. You must have jupyter notebook installed. To run the script, navigate to the src directory and run `jupter notebook` open the [TwitterSentiment.ipynb](src/TwitterSentiment.ipynb) file and run the first cell.

To re-run the R Markdown notebook, you must have R Studio installed. First open [DSCI_542_lab2_swann_kitson.Rproj](DSCI_542_lab2_swann_kitson.Rproj) then click the knit buttun to re-run the analysis and produce the figures. Feel free to modify the code as you like.

**Dependancies:**

Python:

- Python 3
- tweepy
- json
- pandas

R:

```
R version 3.3.1 (2016-06-21)
Platform: x86_64-apple-darwin13.4.0 (64-bit)
Running under: OS X 10.12.1 (Sierra)

locale:
[1] en_CA.UTF-8/en_CA.UTF-8/en_CA.UTF-8/C/en_CA.UTF-8/en_CA.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] knitr_1.14      jsonlite_1.1    tidytext_0.1.2  stringr_1.1.0   dplyr_0.5.0     purrr_0.2.2     readr_1.0.0    
 [8] tidyr_0.6.0     tibble_1.2      ggplot2_2.2.0   tidyverse_1.0.0

loaded via a namespace (and not attached):
 [1] Rcpp_0.12.8       highr_0.6         formatR_1.4       plyr_1.8.4        tokenizers_0.1.4  tools_3.3.1      
 [7] digest_0.6.10     evaluate_0.10     gtable_0.2.0      nlme_3.1-128      lattice_0.20-33   Matrix_1.2-6     
[13] psych_1.6.9       DBI_0.5-1         yaml_2.1.13       parallel_3.3.1    janeaustenr_0.1.4 grid_3.3.1       
[19] R6_2.2.0          foreign_0.8-66    rmarkdown_1.1     reshape2_1.4.2    magrittr_1.5      htmltools_0.3.5  
[25] scales_0.4.1      SnowballC_0.5.1   assertthat_0.1    mnormt_1.5-5      colorspace_1.3-1  labeling_0.3     
[31] stringi_1.1.2     lazyeval_0.2.0    munsell_0.4.3     broom_0.4.1  
```