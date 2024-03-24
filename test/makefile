NAME    =    math
RM      =     rm -f
CCPP  	=  		gcc
CFLAG   =     -Wall -Werror -Wextra -std=c++98
SRC     =     main.c

OBJ     =     $(SRC:.c=.o)

all : $(NAME)

$(NAME) : $(OBJ)
	$(CCPP) $(OBJ) $(CFLAG) -o $@

%.o : %.cpp
	$(CCPP) $(CFLAG) -o $@ -c $^

clean :
	$(RM) $(OBJ) $(OBJSB)

fclean : clean
	$(RM) $(NAME)

re : fclean all
