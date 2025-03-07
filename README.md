
Welcome to **Libft** – a fun and practical rework of many standard C library functions. This project was the first one in 42 curriculum in Hive Helsinki. It gave me a hands-on opportunity to really understand how C works at its core, from memory management to pointer magic. Plus, it’s a cool way to build a library that you can reuse in future projects!

---

## Table of Contents

- [Overview](#overview)
- [What's Inside](#whats-inside)
- [Why This Project Matters](#why-this-project-matters)
- [Usage](#usage)

---

## Overview

Libft is all about re-implementing familiar standard library functions (with an `ft_` prefix) and adding a few extra ones. By doing so, I got to dive deep into:

- **Memory Management:** Learning how allocation, deallocation, and memory leaks work.
- **Pointers & Data Handling:** Manipulating data at the very low-level with pointers.
- **C Fundamentals:** Getting a better grip on how C handles strings, numbers, and more.

This project isn’t just a coding exercise; it’s a journey into the very heart of how computers work with data.

---

## What's Inside

### Mandatory Functions
These are the core functions reworked from the standard C library:
- **ft_isalpha**  
- **ft_isdigit**  
- **ft_isalnum**  
- **ft_isascii**  
- **ft_isprint**  
- **ft_strlen**  
- **ft_memset**  
- **ft_bzero**  
- **ft_memcpy**  
- **ft_memmove**  
- **ft_strlcpy**  
- **ft_strlcat**  
- **ft_toupper**  
- **ft_tolower**  
- **ft_strchr**  
- **ft_strrchr**  
- **ft_strncmp**  
- **ft_memchr**  
- **ft_memcmp**  
- **ft_strnstr**  
- **ft_atoi**  
- **ft_calloc** (uses `malloc()`)  
- **ft_strdup** (uses `malloc()`)

### Additional Functions
These extra functions add more tools for string and memory manipulation:
- **ft_substr**  
- **ft_strjoin**  
- **ft_strtrim**  
- **ft_split**  
- **ft_itoa**  
- **ft_strmapi**  
- **ft_striteri**  
- **ft_putchar_fd**  
- **ft_putstr_fd**  
- **ft_putendl_fd**  
- **ft_putnbr_fd**

### Bonus (Linked List) Functions
If you’re up for even more fun, try these out:
- **ft_lstnew**  
- **ft_lstadd_front**  
- **ft_lstsize**  
- **ft_lstlast**  
- **ft_lstadd_back**  
- **ft_lstdelone**  
- **ft_lstclear**  
- **ft_lstiter**  
- **ft_lstmap**

---

## Why This Project Matters

Recreating these functions isn’t just about rewriting basic level library code — it’s a fantastic learning experience:

- **Understanding Memory:**  
  Every call to `malloc()` or `free()` helped me visualize how dynamic memory allocation works in C. No more mysterious segfaults!

- **Demystifying the Standard Library:**  
  Ever wonder how `strlen` or `memcpy` work under the hood? By coding them yourself, you see the details that make them tick.

- **Strengthening Pointers:**  
  Pointers can be tricky, but they’re the backbone of C. This project made me comfortable with pointer arithmetic, data addressing, and more.

- **Building a Reusable Tool:**  
  Besides learning, you end up with your own library that you can plug into future projects—saving you time and giving you a deeper understanding of your code.

---

## Usage

Once you’ve compiled your library with the provided Makefile, linking it to your project is a breeze. Here’s a quick example:

```bash
# Compile the library
make

# Compile your program with the library
gcc -Wall -Wextra -Werror your_program.c libft.a -o your_program
```
