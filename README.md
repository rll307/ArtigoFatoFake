# General Information

This repository describes the methods used in our article: "AVALIATIVIDADE EM COMENTÁRIOS EM POSTAGENS DEDICADAS À VERIFICAÇÃO DE NOTÍCIAS FALSAS NAS ELEIÇÕES PRESIDENCIAIS DE 2018". 

The authors are:

- Rodrigo Esteves de Lima Lopes - UNICAMP [email](mailto:rll307@unicamp,br) 
- Karen Mercuri Macedo - UNICAMP [email](mailto:karen.tmm@gmail.com ) 
- Maristella Gabardo - IFPR [email](mailto:maris.gabardo@ifpr.edu.br)

The article is still in peer evaluation, soon as we have it published, we will post it here. 

The files describe the many processes the research had:

1. Data collection
1. R scripts for data analysis 
	- R scripts for visualisation
	- R scripts for concordancing



#Data collection
The data in this article was collect from somes posts by [Fato ou Fake](https://g1.globo.com/fato-ou-fake/) in [Facebook](https://pt-br.facebook.com/fatooufake/), a information checking agency in Brazil. Please, see the article for specific dates. 

Unfortunately, the tool used for data collection, Netvizz, is no longer working because of Facebook new regulations. Today an alternative would be [Facepage](https://github.com/strohne/Facepager). 


#Data Analysis
All data was analised using [R](https://www.r-project.org/), the following pacakes were part of our methodology:

1. [Quanteda](https://quanteda.io/): Package for text-data processing and concordancing
2. [Ggplot2](https://ggplot2.tidyverse.org/): Package for data visualisation
3. [Dplyr](https://dplyr.tidyverse.org/): Package for data manipulation
4. [Forcats](https://forcats.tidyverse.org/): Package for handling categorical variables

## Detailed scripts for analysis and visualisation
For a detailed script on analysis and file visualisation, please access:

- scritp.html
	- For a html tutorial
- script.R
	- For a R script
