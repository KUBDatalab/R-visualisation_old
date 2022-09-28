---
title: Setup FIXME
---

## Setting up R and RStudio 


## Getting ready to plot!
Before we do anything else, we need to make sure that we have installed the necessary libraries.

```{r installing libraries, eval=F}
install.packages("tidyverse")
```

After installing the libraries, we load the libraries, so we can use them:

```{r}
library(tidyverse)
```

## Hvilke data arbejder vi med

Vi arbejder med en klassiker. Diamanter.

```{r}
head(diamonds)
```

Datasættet diamonds er indbygget i ggplot2. Det indeholder priser på 53,940 diamanter,
og parametre på dem:

- carat: diamantens vægt i karat (0.200 gram)
- cut Kvaliteten af hvordan diamanten er slebet (Fair, Good, Very Good, Premium, Ideal)
- color. farven - fra D (der er bedst), til J (der er dårligst)
- clarity et mål for hvor klar diamanten er. Kategorisk variabel, "I1" (dårligst), "SI2", "SI1", "VS2", "VS1", "VVS2", "VVS1", "IF" (bedst)
- depth total depth percentage (øh? z divideret med middelværdien af x og y)
- table bredden af toppen - relativt til det bredeste punkt
- price. I USD
- x længde i mm
- y bredde i mm
- z dybde i mm


{% include links.md %}
