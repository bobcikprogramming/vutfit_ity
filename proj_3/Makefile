NAME = proj3

$(NAME).pdf: $(NAME).ps
	ps2pdf $(NAME).ps

$(NAME).ps: $(NAME).dvi
	dvips -sPAPERSIZE=a4 $(NAME).dvi

$(NAME).dvi: $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex

c: clean
clean:
	rm -f $(NAME).dvi $(NAME).log $(NAME).blg $(NAME).bbl $(NAME).toc $(NAME).aux $(NAME).out $(NAME).lof $(NAME).ptc


