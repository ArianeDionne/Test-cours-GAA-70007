Projet\_test\_cours
================
Ariane Dionne
2020-06-12

## Introduction

Ceci est en **gras**

Ceci est en *italique*

Ceci est en `largeur fixe`

Ceci est une liste

1.  Item 1
2.  Item 2
3.  Item 3
      - Item 3a
      - Item 3b

Ceci est une équation \(c = \sqrt{a^2 + b^2}\)

Ceci est une image ![nom de l’image](photos/work.jpg)

[Journal](www.ledevoir.com)

Dictum fusce ut placerat orci nulla pellentesque dignissim enim. Potenti
nullam ac tortor vitae purus. Mattis vulputate enim nulla aliquet. Magna
fringilla urna porttitor rhoncus dolor purus non enim. Lectus proin nibh
nisl condimentum id venenatis a condimentum. Malesuada proin libero nunc
consequat interdum varius sit. Vel pharetra vel turpis nunc eget lorem
dolor. Rhoncus aenean vel elit scelerisque mauris pellentesque pulvinar
pellentesque. Gravida quis blandit turpis cursus in hac habitasse
platea. Ut aliquam purus sit amet luctus venenatis lectus magna.

``` r
a <- "ours"
b <- "polaire"
paste(a,b)
```

    ## [1] "ours polaire"

The data and the R code used to compute the results are both available
as supplementary material at
[lien](https://github.com/ArianeDionne/Test-cours-GAA-70007.git)

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Test-markdown_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
