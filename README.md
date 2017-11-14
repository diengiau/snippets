# 1. About: snippets
All my snippets in R, Stata, ...

This repository is to save all my snippets.

# 2. How to install:
## 2.1 For Rstudio
To install it to Rstudio: following this [snippr](https://github.com/dgrtwo/snippr) package.

```{r}
# install snippr
devtools::install_github("dgrtwo/snippr")

# load it
library(snippr)

# install my snippets to Rstudio
snippets_install_github("diengiau/snippets")
snippets_install_github("diengiau/snippets", language = "r") # to specify the language

# install only one snippet file
snippets_install_github("diengiau/snippets", language = "r", name = "r") # only install r.snippets
snippets_install_github("diengiau/snippets", language = "r", name = "markdown") # only install markdown
```

## 2.2 For Sublime Text
Copy the file and paste to the User data folder in your installed or portable Sublime folder. Check it by yourself because it may change by each system.
