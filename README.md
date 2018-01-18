# The Six W's About R packages

Many R users struggle with R packages. The problem is largely because the useful information is scattered or burried in text written mainly for developers, the fairly experienced fellows who create R packages (e.g. the [R Packages](http://r-pkgs.had.co.nz/) book by Hadley Wickham, and [these slides](https://speakerdeck.com/jennybc/ubc-stat545-2015-writing-your-first-r-package) by Jenny Bryan). This document helps R users to understand and use R packages by briefly answering the [Six W's](https://en.wikipedia.org/wiki/Five_Ws) about R packages, targetting specifically an imaginary R user with no background.



# What Is An R Package?
* Quote definition from rpkgs or JB slides
* Image of devtools cheetsheet

## Definition
An R package is a kind of _Inflatable Castle_: A castle that inflates. An _Inflatable Castle_ can be big and red, but it can't have a massive hole -- the hole won't let it inflate, so if your castle has a massive hole it is no longer an _Inflatable Castle_. (Sad, I know). Similarly, an R package is a very specific collection of files and folders. To meet the definition of "R package", the names and structure of those files and folders have to meet some expectations. If you doon't meet them, you have files and folders but not an R package.

## Source Versus Built
Can you have a deflated _Inflatable Castle_? Yes you can. The deflated _Inflatable Castle_ isn't good for jumping on, but it is good for other things, like cleaning it. Similarly, to clean or maintain an R package you need its "deflated" or source state. The source of a package has all you need to build it but you can't use it for its main purpose until you actually build it. This built, "inflated", state of an R package is what you use to have fun.

## The Useful Stuff In An R Package
(What is each of these items? Link to examples)
* Functions (computer programs)
* Data
* Index: 
* Descriptons
* Help files
* Dependencies

# Why Is An R Package Useful?
An R package is useful because it makes it easy to share and use the functions (computer programs) and/or the data that it contains, and the documents that explain how to use those functions (See What Is An R Package > The Useful Stuff In An R Package xxx_add_link). An R package makes all its components available from one place: The R console. Thus R packages help you to find what you need quickly. Thay way you can spend most of your time working on whatever you want to accomplish rather than on the mundane task of searching for auxiliary information scattered in your computer or online. Having everything you need structured as an R package is convenient.

# Who creates, maintains, and uses an R package?
* Anyone can create an R package. 
* If the package to be shared, someone must maintain it

# Where does an R package live?
* Your computer
* CRAN
* Git Hub
* Other repositories (xxx_examples from `install_REPOSITORY()`)

# When Is An R Packages Created, Shared, Used, And Updated?
* Created in someone's computer.
* Shared whenever they are ready
    * Explain the concept of pre-release and release (CRAN, GitHub, devtools::release\*()).
* Updated whenever the maintainer wants.
* [Installing older versions of packages](https://support.rstudio.com/hc/en-us/articles/219949047-Installing-older-versions-of-packages?mobile_site=true)


# How To Find, Install, And Use An R Package?
## Find An R Packages
* Point to blog about how to find R packages

## Install An R Package
* `install.packages()`
* __remotes__ and __devtools__
    * install_github()`
    * install_REPOSITORY()`

## Uninstall An R Package
* Always with `remove.packages()`, regardless of where you installed it from.

## Use An R Package


# Summary

xxx Compose a paragraph with the key content of each of the six w's.

# Resources

*  R packages book
* Jenny Bryan's slides
* RStudio community
* RStudio.cloud/primer
* RStudio webinars
* RStudio articles
