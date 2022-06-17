# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: smikayel <smikayel@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/03/24 20:10:50 by smikayel          #+#    #+#              #
#    Updated: 2022/06/06 16:22:11 by smikayel         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

MINILIBIX = ./libmlx.dylib

NAME = TandJ

SRCS =	./sources/*c ./*c

CC = cc

FLAGS = -Wall -Wextra -Werror

OUTPUT = -o $(NAME)

all : 
	@$(CC) $(FLAGS) $(MINILIBIX) $(SRCS) $(OUTPUT)
	@echo "\033[0;92m $(NAME) Done, Have a good game! ✓"

clean :
	@echo "\033[0;91m There is only output file to clear use fclean for it"

fclean :
	@rm -rf $(NAME)
	@echo "\033[0;92m Fully cleaned ✓"

re : fclean all
