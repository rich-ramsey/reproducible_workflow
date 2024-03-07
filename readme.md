This project tries to outline a reproducible workflow that starts with the raw data and ends with the finished manuscript.

It is intended to be a live document that is updated over time. 
The latest version will be stored on github.

# Intended audience #

This is mainly for my lab members. For relevant context, my lab is interested in experimental psychology and cognitive neuroscience.

But other folks might also find it useful as a general way to organise a more reproducible workflow.

# Basic components of the workflow #

- [renv()](https://rstudio.github.io/renv/articles/renv.html) to manage R package versions
- [git](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) for version control
- [GitHub](https://github.com/) for collaborating and sharing coding
- The [Tidyverse](https://www.tidyverse.org/) ecosystem for data wrangling and visualisation 
- [brms](https://paul-buerkner.github.io/brms/) for building Bayesian regression models
- The [papaja()](https://frederikaust.com/papaja_man/) package for writing reproducible manuscripts

As you can see, all I am doing here is combining a bunch of packages and processes into one workflow.
There is nothing inherently novel in the workflow I present, just one worked example of how to combine a set of processes.

# What's the easiest way to access the project? #

If you just want to read along, then hit the tutorial.html or tutorial.pdf file and take a look.

If you want to see and work with the code, then:

1. Clone or download the project from github to your local machine.
2. Open the reproducible_workflow.Rproj file and renv() will automatically bootstrap itself.
3. renv() will then ask if you want use renv::restore() to install all of the packages. Say yes.
4. At this point, you can use the project with the same package versions that were stored in the renv.lock file.


