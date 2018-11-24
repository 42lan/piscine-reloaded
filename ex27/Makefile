# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: amalsago <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/08 16:26:58 by amalsago          #+#    #+#              #
#    Updated: 2018/11/08 19:49:24 by amalsago         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC=gcc
CFLAGS=-Wall -Wextra -Werror
NAME=ft_display_file
SRCS=$(wildcard ./*.c)
OBJ=$(SRCS:.c=.o) 
HEADERS=$(wildcard ./*.h)

all:
	$(CC) $(CFLAGS) -c $(SRCS)
	$(CC) -o $(NAME) $(CFLAGS) $(SRCS)

clean:
	/bin/rm -f $(OBJ)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
