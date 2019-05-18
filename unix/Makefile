# LaTex Makefile

CC	:= pdflatex
CFLAGS	:=

NAME	:= unix.pdf
SRCS	:= unix.tex

.PHONY : all clean fclean re

all : $(NAME)

$(NAME) : $(SRCS)
	$(CC) $(CFLAGS) $<

clean :
	rm -f *.log *.aux *.toc

fclean : clean
	rm -f *.pdf
re : fclean all
