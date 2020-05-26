NAME	= irrlicht

CC	= g++

RM	= rm -f

SRCS	= ./main.cpp

CFLAGS = -I ./
CFLAGS += -Wall -Wextra

all: clear $(NAME) 

$(NAME):
	 $(CC) -g3 $(SRCS) -o $(NAME) $(CFLAGS) -lIrrlicht -lXxf86vm -lXrandr -lGL -lGLU -lXi -lX11

clear:
	@ $(RM) $(NAME)

clean:
	@ $(RM) $(NAME)
	 @echo "\033[0;31m Cleaning. \033[0m" "."".""."
	 @sleep 1	
	 
fclean:
	@ $(RM) $(NAME)
	 @echo "\033[0;31m Cleaning. \033[0m" "."".""."
	 @sleep 1

re: fclean all
	
.PHONY: all clean fclean re
