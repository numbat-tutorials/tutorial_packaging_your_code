# Packaging and sharing your code

Website: https://numbat-tutorials.github.io/tutorial_packaging_your_code

---

Sharing your R code doesn’t have to be a messy email chain or a zip file with cryptic scripts. In this hands-on workshop, you’ll learn how to wrap your code into a professional R package that’s easy to use, easy to share, and easy to maintain. We’ll guide you through the whole process—from setting up the structure to documenting your functions and publishing your work online, including websites for your documentation and submission to CRAN.

### Presenters

* [Michael Lydeamore](https://www.michaellydeamore.com) is a senior lecturer in the Department of Econometrics and Business Statistics. His research focuses on computational statistics, and network theory, applied to public health and infectious diseases problems. Dr Lydeamore is a Fellow of the Higher Education Academy, and editor for Royal Society Open Science and the Bulletin of Mathematical Biology. He is also currently a board member and treasurer for the [Australia and New Zealand Industrial and Applied Mathematics](http://www.anziam.org.au) society.

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

---

### Session 2: Sharing your code on the web

This session will show you how you can share your code to others on the internet. This will include:

* Syncing your code with git and GitHub
* Hosting your documentation online using `roxygen2` and `pkgdown`
* Checklists for submission of your package to CRAN, including testing on various platforms using [rhub](https://r-hub.github.io/rhub/index.html).
* Preventing common reasons for package rejection by CRAN moderators

## Getting started

1. Ensure you have R and RStudio by following [these instructions](https://startr.numbat.space/modules/starter/installation/)
2. Set up a [GitHub](https://docs.github.com/en/get-started) account if you don't already have one, and make sure your SSH keys are set up. It's not essential for this workshop but eventually your package should be made available in a GitHub repo, so this is a good time to start.
3. Install Quarto from [here](https://quarto.org/docs/get-started/)
4. Install the required packages for the workshop:  
```{r}
install.packages(c("pkgdown","usethis","devtools"))
```

Copyright: Michael Lydeamore 2025

These materials are licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
