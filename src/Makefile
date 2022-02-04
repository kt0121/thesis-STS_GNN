THESIS 			= thesis
INTRODUCTION	= introduction
RELATEDWORK 	= relatedwork
METHOD			= method
EXPERIMENT		= experiment
DISCUSSION		= discussion
CONCLUSION 		= conclusion

TEX				= .tex
DVI				= .dvi
PDF 			= .pdf

#--------------------------------------------#

all:
	rm -f $(THESIS)$(PDF)
	platex $(THESIS)$(TEX)
#	pbibtex $(THESIS)
	platex $(THESIS)$(TEX)
	platex $(THESIS)$(TEX)
	dvipdfmx $(THESIS)$(DVI)

introduction:
	rm -f $(INTRODUCTION)$(PDF)
	platex $(INTRODUCTION)$(TEX)
#	pbibtex $(INTRODUCTION)
	platex $(INTRODUCTION)$(TEX)
	platex $(INTRODUCTION)$(TEX)
	dvipdfmx $(INTRODUCTION)$(DVI)

relatedwork:
	rm -f $(RELATEDWORK)$(PDF)
	platex $(RELATEDWORK)$(TEX)
#	pbibtex $(METHOD)
	platex $(RELATEDWORK)$(TEX)
	platex $(RELATEDWORK)$(TEX)
	dvipdfmx $(RELATEDWORK)$(DVI)

method:
	rm -f $(METHOD)$(PDF)
	platex $(METHOD)$(TEX)
#	pbibtex $(METHOD)
	platex $(METHOD)$(TEX)
	platex $(METHOD)$(TEX)
	dvipdfmx $(METHOD)$(DVI)

experiment:
	rm -f $(EXPERIMENT)$(PDF)
	platex $(EXPERIMENT)$(TEX)
#	pbibtex $(EXPERIMENT)
	platex $(EXPERIMENT)$(TEX)
	platex $(EXPERIMENT)$(TEX)
	dvipdfmx $(EXPERIMENT)$(DVI)

#discussion:
#	rm -f $(DISCUSSION)$(PDF)
#	platex $(DISCUSSION)$(TEX)
#	pbibtex $(DISCUSSION)
#	platex $(DISCUSSION)$(TEX)
#	platex $(DISCUSSION)$(TEX)
#	dvipdfmx $(DISCUSSION)$(DVI)

conclusion:
	rm -f $(CONCLUSION)$(PDF)
	platex $(CONCLUSION)$(TEX)
#	pbibtex $(CONCLUSION)
	platex $(CONCLUSION)$(TEX)
	platex $(CONCLUSION)$(TEX)
	dvipdfmx $(CONCLUSION)$(DVI)

clean:
	rm -f *.aux *.dvi *.log *.blg *.bbl

allclean:
	make clean
	rm -f *.pdf
