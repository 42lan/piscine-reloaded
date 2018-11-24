# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: amalsago <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/07 17:02:13 by amalsago          #+#    #+#              #
#    Updated: 2018/11/08 14:00:05 by amalsago         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC=gcc
CFLAGS=-Wall -Wextra -Werror
NAME=libft.a
SRCS=$(wildcard ./srcs/*.c)
OBJ=$(SRCS:.c=.o) 
HEADERS=$(wildcard ./includes/*.h)

all: $(NAME)
	ar -rc $(NAME) $(OBJ:./srcs/%=%) 
	ranlib $(NAME)

$(NAME):
	$(CC) $(CFLAGS) -c $(SRCS)

clean:
	/bin/rm -f $(OBJ:./srcs/%=%)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
