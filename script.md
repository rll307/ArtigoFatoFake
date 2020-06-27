Script for article:  
AVALIATIVIDADE EM COMENTÁRIOS EM POSTAGENS DEDICADAS À VERIFICAÇÃO DE
NOTÍCIAS FALSAS NAS ELEIÇÕES PRESIDENCIAIS DE 2018
================
\- Rodrigo Esteves de Lima-Lopes  
State University of Campinas  
<rll307@unicamp.br>  
\- Karen Mercuri Macedo  
State University of Campinas  
<karen.tmm@gmail.com>  
\- Maristella Gabardo  
Instituto Federal do Paraná  
<maris.gabardo@ifpr.edu.br>

# Thank you note

We hope this script is useful for researchers in fields of linguistics
and applied linguistics. Unfortunally due to regulations form the
committee for research ethics, we cannot provide data in this
repository. If you have any further questions, please feel free to drup
us a line.

# General Information

This repository describes the methods used in our article:
“AVALIATIVIDADE EM COMENTÁRIOS EM POSTAGENS DEDICADAS À VERIFICAÇÃO DE
NOTÍCIAS FALSAS NAS ELEIÇÕES PRESIDENCIAIS DE 2018”.

The article is still in peer evaluation, soon as we have it published,
we will post it here.

This guide describes the many procedures we had during the research had:

1.  Data collection
2.  R scripts for data analysis
      - R scripts for visualisation
      - R scripts for concordancing

# Loading packages

Each of this packages has a funcion in data analysis:

1.  [Quanteda](https://quanteda.io/): Package for text-data processing
    and concordancing
2.  [Ggplot2](https://ggplot2.tidyverse.org/): Package for data
    visualisation
3.  [Dplyr](https://dplyr.tidyverse.org/): Package for data manipulation
4.  [Forcats](https://forcats.tidyverse.org/): Package for handling
    categorical variables
5.  [Readr](https://github.com/tidyverse/readr): Package for reading CSV
    (an other kinds) of rectangular data

<!-- end list -->

``` r
library(quanteda)
library(readr)
library(ggplot2)
library(dplyr)
library(forcats)
```

After the packages were loaded, it is time to load the comments
