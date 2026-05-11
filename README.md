# Libft

A C library that reimplements standard functions from the C standard library.

## What it does

Libft is a personal C library built from scratch. It reimplements common functions such as `strlen`, `strdup`, `atoi`, `memset`, and many others. It also includes utility functions for linked lists and string manipulation that are not part of the standard library.

This library is used as a foundation in all subsequent 42 projects.

## Functions included

**String functions:** `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strlcpy`, `ft_strlcat`, `ft_strdup`, `ft_strnstr`, `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`

**Memory functions:** `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`

**Character checks:** `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`

**Conversion:** `ft_atoi`, `ft_itoa`

**Output:** `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

**Linked lists:** `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstsize`, `ft_lstlast`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## Usage

```sh
make
```

This produces `libft.a`, which can be linked to any C project:

```sh
cc main.c -L. -lft
```

## Project context

This is the first project at School 42. The goal is to understand how standard C functions work internally and to build a reusable toolkit for future projects.