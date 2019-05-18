# LaTex Makefile

CC	:= pdflatex
CFLAGS	:=

NAME	:= objc.pdf
SRCS	:= objc.tex

.PHONY : all clean fclean re

all : $(NAME)

$(NAME) : $(SRCS)
	$(CC) $(CFLAGS) $<

clean :
	rm -f *.log *.toc *.aux

fclean : clean
	rm -f *.pdf
re : fclean all
