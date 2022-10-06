MBIO630_IndividualProject
================
InsertYourName
2022-10-06

## Introduction to using R Markdown documents

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button above, a document will be generated
that includes both content as well as the output of any embedded R code
chunks within the document.

#### Code chunks

You can embed an R code chunk like this:

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

#### Including Plots

You can also embed plots, for example:

![](MBIO630_IndividualProject_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

## Final project goals

-   Help students address a question related to their interest that can
    be answered using remote sensing  
-   Provide experience with developing and refining research questions  
-   Provide experience with proposal development and writing  
-   Provide experience with manuscript-writing  
-   Provide experience with giving presentations  
-   (potentially) Form the seed of a publishable manuscript / thesis
    chapter

## Final project guidelines

-   You will write up your project as a ‘mini-paper’, i.e., a shorter
    and less formal version of a manuscript you’d submit for
    publication - If you’re new to writing manuscripts, [this is a handy
    guide](https://conservationbytes.com/2012/10/22/how-to-write-a-scientific-paper/)
    that lays out the process in clear steps
-   Text length (excluding references) should be between 2000-3000 words
-   Format should follow standard scientific writing sections (Abstract,
    Introduction, Methods, Results, and Discussion)
-   You should include 3-6 figures or display items of some sort
-   You can include references as needed (i.e., where it supports what
    you’re saying), but there is no minimum number of references you
    need in whichever sort of standard reference format you like (one
    example is in the [journal “Nature”’s formatting
    guidelines](https://www.nature.com/nature/for-authors/formatting-guide)).
-   How to set up and turn in your project:
    -   Write your project as a R Markdown document in a project folder
        setup as we’ve done in the course up to now
        -   If you’re new to RMarkdown, use the cheat sheets in the
            “info” folder to help with your write-up
    -   Follow the [data and code tutorial found
        here](https://jmadinlab.github.io/data_code_tutorial/) to both
        know how to set up your project folder structure (this is just
        for your benefit and won’t be graded, but will help you)
    -   Upload it as a new repository in YOUR Github workspace (not the
        course github workspace)
    -   The link above also gives step-by-step instructions for how to
        get your project set up with git and uploaded to Github
        -   If you have trouble with git/Github after following the
            steps in this guide, reach out to one of the instructors.
    -   You will turn your project in by uploading it to Github and
        adding me as a collaborator
        -   in your repo, do this by: Settings -\> Collaborators (left
            hand side bar) -\> Add People (green button)
    -   Due date: Oct. 19, 5 pm

## Template for final project

When you feel relatively comfortable in creating your R Markdown (.Rmd)
document and are ready to insert your text, figures, and any tables or
analyses, you can delete everything above, from this section through
“\## Introduction to using R Markdown documents” and use the rest of
this document as your template for your final project write-up (so you
don’t have to create it from scratch, since R Markdown is new to some of
you).

## Abstract

(insert your text here)

## Introduction

(insert your text here)

## Methods

(insert your text here)

## Results

(insert your figures, tables (if any), and text here; example of code
chunks are given below so you can use this format and insert your own
code in place of the example code)

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

![](MBIO630_IndividualProject_files/figure-gfm/plots%20chunk%201-1.png)<!-- -->

## Discussion

(insert your text here)

## References

(insert your references here)
