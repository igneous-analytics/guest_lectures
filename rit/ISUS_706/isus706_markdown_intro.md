---
title: "R & R Markdown"
author: "Chip Galusha"
date: "10/20/2019"
output: 
  html_document:
    toc: true
    toc_depth: 2
    toc_float: true
    code_folding: hide
    keep_md: true
---



## Introduction

The nice looking document is an R Markdown document. It was developed in the R Studio environment. Unfortunately the 
R Studio integerated formatting did not exists when I when through graduate school and I was left to write papers in
either Laetx or a blend of MS Word and excel(eek.). Both are very tedious compared to the markdown formatting syntax 
that enables the users to author HTML, PDF, MS Word documents, and many other formats. 

The aim of this document is to inspire the reader, regardless of their programming background, to author documents
that require the presentation of graphs, data, formulas, or all of the above using this syntatial format. It is not 
intended to be a comprehensive reference to R markdown or the markdown markup language. Links to such material can be 
found in the appendix.

## Getting Started 

Once you've successfully opened R studio, use the document with the green + in the top left to create a new 
Mardown document. This action will prompt a new window where you can enter the document's and select the default output
format. Both of these options can be changed when the document is being edited. Clicking OK will create a untitled
.Rmd document.

## R Markdown Content {.tabset .tabset-fad}
Makdown files contain three types of content:   
* A YAML header surrponded by `---`s   
* R code chucks surronded by ```s   
* test mised with simple text formatting   

### YAML Header
The YAML header controls the general formatting of the document. Options will vary depending on the output format you've
selected. The HTLM format, used for the this document, has the most profuse options. This is due in large part to the
fact the markdown was originally an HTML output.

### Code Chunks

##$ General Text Formatting



## Code Chunks

## Presenting Data
### DT Package







This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Including Plots

You can also embed plots, for example:

![](isus706_markdown_intro_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
