# Packaging and sharing your code

Website: https://numbat-tutorials.github.io/tutorial_packaging_your_code

### Presenters

* [Michael Lydeamore](https://www.michaellydeamore.com) is a senior lecturer in the Department of Econometrics and Business Statistics. His research focusses on computational statistics, and network theory, applied to public health and infectious diseases problems. Dr Lydeamore is a Fellow of the Higher Education Academy, and editor for Royal Society Open Science and the Bulletin of Mathematical Biology. He is also currently a board member and treasurer for the [Australia and New Zealand Industrial and Applied Mathematics](http://www.anziam.org.au) society.

### Background

You will need a basic understanding of R to the level explained in [R4DS](https://r4ds.hadley.nz/). Some knowledge of Quarto or RMarkdown will be useful.

Knowledge of `git`, and an ability to use GitHub will be required. **Please ensure you have a GitHub account ready for this tutorial**.

## Structure of the tutorial

### Session 1: Creating a package for your code

This session will guide you through creating your first package for your code. This will include:

* R Package structure and key files
* How to include your R functions
* Inclusion and processing of data
* Setting up your package for version control
* Documenting your code to view inside R
* Writing examples and vignettes

### Session 2: Sharing your code on the web

This session will show you how you can share your code to others on the internet. This will include:

* Syncing your code with git and GitHub
* Hosting your documentation online using `roxygen2` and `pkgdown`
* Checklists for submission of your package to CRAN
* Preventing common reasons for package rejection by CRAN moderators

## Getting started

1. Ensure you have R and RStudio by following [these instructions](https://startr.numbat.space/modules/starter/installation/)
2. Set up a GitHub account if you don't already have one, and make sure your SSH keys are set up.
3. Install Quarto from [here](https://quarto.org/docs/get-started/)
4. Install the required packages for the workshop:  
```{r}
install.packages(c("pkgdown","usethis","devtools"))
```