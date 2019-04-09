
## Install

```
brew install r
brew install pandoc 
brew install pandoc-citeproc
```

`r` starts the REPL, then install packages 

```
install.packages("rmarkdown")
install.packages("DT")
```

## Render files

```
rscript -e "rmarkdown::render('hello.rmd')"

rscript -e "rmarkdown::render('sample.Rmd', c('html_document'), clean=FALSE)"
```
