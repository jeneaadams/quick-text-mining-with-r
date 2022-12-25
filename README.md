# Introduction 

While writing a grant for [BWCB](http://blackwomencompbio.org), I wanted to improve some data visualization strategies to communicate certain demographics of our membership. Of these metrics is member area of expertise, which is a free-response section on the BWCB member application. I knew I would need to dive into a new tool, so here I show what I've learned and look forward to using in the future with regard to text mining in R.

References: 

https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html

https://books.psychstat.org/textmining/index.html#contents

https://cran.r-project.org/web/packages/ggraph/vignettes/Layouts.html

http://users.dimi.uniud.it/~massimo.franceschet/ns/syllabus/make/ggraph/ggraph.html 


![](https://static.wixstatic.com/media/879f01_5359da7bf47d4241b1914ccee579eb92~mv2.png/v1/fill/w_200,h_80,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/879f01_794561c3f6874b4e8452329f0476bfee~mv2_edited.png)

![](https://static.wixstatic.com/media/879f01_f27d2a4ddd4a4f288f7ea2ca8acbd064~mv2.png/v1/fill/w_194,h_194,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/879f01_f27d2a4ddd4a4f288f7ea2ca8acbd064~mv2.png)

[Jenea I. Adams Website](http://jeneaiadams.com)

# Data 
2022 Member area of expertise data from the Black Women in Computational Biology Network

# Packages 
```
library(readr)
library(ggplot2)
library(tidyr)
library(tidytext)
library(dplyr)
library(igraph)
library(ggraph)
```
