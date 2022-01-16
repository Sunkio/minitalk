# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: tschmidt <tschmidt@student.42wolfsburg.de> +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/10/10 06:37:41 by tschmidt          #+#    #+#              #
#    Updated: 2022/01/15 12:21:33 by user             ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC = gcc

CFLAGS = -c -Wall -Wextra -Werror

NAME = libftprintf.a

SRC = ft_printf.c utils/utils_1.c utils/utils_2.c

OBJ = ${SRC:.c=.o}

all: $(NAME)

$(NAME): $(OBJ)
	ar -crs $(NAME) $(OBJ)

clean:
	-/bin/rm -f $(OBJ)
	@echo Clean done

fclean: clean
	-/bin/rm -f $(NAME)
	@echo Fclean done

re: fclean all

.PHONY: all objects clean fclean re bonus objectsb
