---
title: The Basics
---

# Remember that you are collaborating:

## Git Pull before work starts. Git add, Git commit, Git push once work pauses.

When you sit down to work on a project, the first thing to do is to do `git pull` (at the bash or zsh command line) or Sync (if you are using the github desktop app) or Pull (if you are using RStudio's git interface).

Whenever you have done some work, more than changing a comma, but less than deleting all of the text and rewriting from scratch, you should do `git add thefile` and then `git commit -m "An explanation about why you did what you did. We don't necessarily need you to explain what you did. We should be able to see that in the diffs."` and then `git push` (or the equivalents in whatever GUI you are using).

## Think in Batch Mode

Although you may build a command file interactively using in [using debugging tools](https://support.rstudio.com/hc/en-us/articles/205612627-Debugging-with-RStudio) or simply using the [debug](https://stat.ethz.ch/R-manual/R-devel/library/base/html/debug.html) mode for functions, **all files should run from start to finish in a fresh directory**. You can do this by never saving .RData files. And by running all command files (including .Rmd and .Rnw files) from scratch at the command line.
