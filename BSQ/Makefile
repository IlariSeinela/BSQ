
NAME = bsq

SRC = main.c funcs.c brains.c map.c

OBJ = main.o funcs.o brains.o map.o

all: $(NAME)

$(NAME):
		@gcc -Wall -Wextra -Werror -c $(SRC)
		@gcc -Wall -Wextra -Werror -o $(NAME) $(SRC)

clean:
		@/bin/rm -f $(OBJ)

fclean: clean
		@/bin/rm -f $(NAME)

re:	fclean all
