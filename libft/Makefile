# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mgonon <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2016/11/03 23:59:50 by mgonon            #+#    #+#              #
#    Updated: 2016/11/04 00:02:36 by mgonon           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_isalpha.c \
	  ft_putchar.c \
	  ft_putendl.c \
	  ft_putnbr.c \
	  ft_putstr.c \
	  ft_strcpy.c \
	  ft_strlen.c \
	  ft_toupper.c \
	  ft_tolower.c \
	  ft_strcat.c \
	  ft_strncat.c \
	  ft_strcpy.c \
	  ft_strncpy.c \
	  ft_strcmp.c \
	  ft_isalnum.c \
	  ft_isdigit.c \
	  ft_isascii.c \
	  ft_isprint.c \
	  ft_isalnum.c \
	  ft_atoi.c \
	  ft_strstr.c \
	  ft_strncmp.c \
	  ft_strclr.c \
	  ft_striter.c \
	  ft_striteri.c \
	  ft_strnstr.c \
	  ft_strmap.c \
	  ft_strmapi.c \
	  ft_strdel.c \
	  ft_strnew.c \
	  ft_memdel.c \
	  ft_memalloc.c \
	  ft_memset.c \
	  ft_strequ.c \
	  ft_strnequ.c \
	  ft_strsub.c \
	  ft_strjoin.c \
	  ft_strtrim.c \
	  ft_strchr.c \
	  ft_strrchr.c \
	  ft_strsplit.c \
	  ft_strdup.c \
	  ft_bzero.c \
	  ft_memcpy.c \
	  ft_memccpy.c \
	  ft_putchar_fd.c \
	  ft_putstr_fd.c \
	  ft_putendl_fd.c \
	  ft_putnbr_fd.c \
	  ft_memcmp.c \
	  ft_memchr.c \
	  ft_memmove.c \
	  ft_itoa.c \
	  ft_strlcat.c \
	  ft_lstnew.c \
	  ft_lstdelone.c \
	  ft_lstdel.c \
	  ft_lstadd.c \
	  ft_lstiter.c \
	  ft_lstmap.c \
	  get_next_line.c \

OBJ = ft_isalpha.o \
	ft_putchar.o \
	ft_putendl.o \
	ft_putnbr.o \
	ft_putstr.o \
	ft_strcpy.o \
	ft_strlen.o \
	ft_toupper.o \
	ft_tolower.o \
	ft_strcat.o \
	ft_strncat.o \
	ft_strcpy.o \
	ft_strcmp.o \
	ft_isalnum.o \
	ft_isdigit.o \
	ft_isascii.o \
	ft_isprint.o \
	ft_isalnum.o \
	ft_atoi.o \
	ft_strstr.o \
	ft_strncmp.o \
	ft_strclr.o \
	ft_striter.o \
	ft_strnstr.o \
	ft_striteri.o \
	ft_strmap.o \
	ft_strmapi.o \
	ft_strdel.o \
	ft_strnew.o \
	ft_memdel.o \
	ft_memalloc.o \
	ft_memset.o \
	ft_strequ.o \
	ft_strnequ.o \
	ft_strsub.o \
	ft_strjoin.o \
	ft_strtrim.o \
	ft_strchr.o \
	ft_strrchr.o \
	ft_strsplit.o \
	ft_strncpy.o \
	ft_strdup.o \
	ft_bzero.o \
	ft_memcpy.o \
	ft_memccpy.o \
	ft_putchar_fd.o \
	ft_putstr_fd.o \
	ft_putendl_fd.o \
	ft_putnbr_fd.o \
	ft_memcmp.o \
	ft_memchr.o \
	ft_memmove.o \
	ft_itoa.o \
	ft_strlcat.o \
	ft_lstnew.o \
	ft_lstdelone.o \
	ft_lstdel.o \
	ft_lstadd.o \
	ft_lstiter.o \
	ft_lstmap.o \
	get_next_line.o \

all: $(NAME)

$(NAME):
	gcc -c -Werror -Wall -Wextra $(SRC)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
