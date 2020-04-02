all: rmarkdown.html

rmarkdown.html: rmarkdown.Rmd my.css
	Rscript -e 'library("rmarkdown"); render("rmarkdown.Rmd")'
