# The Ties of the *Streght of Weak Ties*

Thank for visiting this repo!

## Relevance

Network analysis has emerged as one of the main methodologies to analyze politics, social behaviors, and markets. Mark Granovetter was one of the pioneers in this discipline, his article *The Strength of Weak Ties* (SWT) (1973) was groundbreaking for network analysis and social sciences in general.

Although most of the social scientists who have read Granovetter's work are aware of the relevance of its 1973 paper, a systematic study about of its influence has not been done, to the best knowledge of the author of this article. In this project, I visually explore the impact of SWT regarding three different factors: number of citations, related authors, and topics associated with papers which cite SWT.

## How to visualize the final product?

Please clone the repository in your computer and open Ties.html (the shiny server have some issues that I was not able to solve for the moment –after many many hours of trying–. Sorry for the hassle).

Unfortunately, the data used here is proprietary. Then, please contact me if you run into reproducibility issues.

## Content of the files:

ExploreGranovetter.ipynb is the python code that I utilized as a preprocessing stage.

Ties.Rmd is the code where in set up the flex dashboard.

Paper.pdf is the final report.

## The packages you need to run the main R code (Ties.Rmd) are:

### Graphs and data management

library(sp)

library(htmltools)

library(RColorBrewer)

library(data.table)

library(ggplot2)

library(ggpubr)

### For wordclouds

library("tm")

library("SnowballC")

library("wordcloud")

library("RColorBrewer")
