SOURCE=source.tex
PDF=Test03_Deadlocks_und_Scheduler

all: *tex
	pdflatex -jobname=$(PDF) $(SOURCE)

clean:
	@-rm -rf *.{out,aux,log,pdf}
