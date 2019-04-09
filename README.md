
brew install r
brew install pandoc 
brew install pandoc-citeproc

r   # starts the REPL

install.packages("rmarkdown")
install.packages("DT")      # used by sample.rmd


rscript -e "rmarkdown::render('hello.rmd')"


