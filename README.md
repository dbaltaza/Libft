<h1 align="center">Libft 42 📚 </h1>

```c
            /* ************************************************************************** */
            /*                                                                            */
            /*                                                        :::      ::::::::   */
            /*   Libft                                             :+:      :+:    :+:   */
            /*                                                    +:+ +:+         +:+     */
            /*   By: dbaltaza <marvin@42.fr>                    +#+  +:+       +#+        */
            /*                                                +#+#+#+#+#+   +#+           */
            /*   Created: 2025/10/30 by dbaltaza                  #+#    #+#             */
            /*   Updated: 2025/10/30 by dbaltaza                 ###   ########.fr       */
            /*                                                                            */
            /* ************************************************************************** */
```

## 📋 About the Project

Creation of your own C function library that will be used in future projects.

**Final Grade:** 125/100

---

## 📊 Implemented Functions

### Part 1 - Libc Functions (23/23)
Reimplementation of standard libc functions.

`isalpha` `isdigit` `isalnum` `isascii` `isprint` `strlen` `memset` `bzero` `memcpy` `memmove` `strlcpy` `strlcat` `toupper` `tolower` `strchr` `strrchr` `strncmp` `memchr` `memcmp` `strnstr` `atoi` `calloc` `strdup`

### Part 2 - Additional Functions (11/11)
Useful functions not present in libc.

`substr` `strjoin` `strtrim` `split` `itoa` `strmapi` `striteri` `putchar_fd` `putstr_fd` `putendl_fd` `putnbr_fd`

### Bonus - Linked Lists (9/9)
Linked list manipulation.

`lstnew` `lstadd_front` `lstsize` `lstlast` `lstadd_back` `lstdelone` `lstclear` `lstiter` `lstmap`

---

## 🛠️ Compilation

```bash
make            # Compiles the library
make bonus      # Compiles with bonus
make clean      # Removes objects
make fclean     # Removes everything
make re         # Recompiles
```

---

## 💡 Important Points

✅ All functions pass Norminette  
✅ No memory leaks (tested with valgrind)  
✅ Malloc protection in all allocations  
✅ Makefile doesn't recompile already compiled files  
✅ Bonus only counts if mandatory is perfect

---

## 🧪 How to Test

```bash
# Tripouille Tester
git clone https://github.com/Tripouille/libftTester.git
cd libftTester && make

# Check memory leaks
valgrind --leak-check=full ./your_test
```

---

**Made by:** dbaltaza  
**Campus:** 42 Lisboa  
**Year:** 2025
