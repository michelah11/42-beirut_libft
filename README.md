<h1 align="center">Libft</h1>

<p align="center">
  <strong>42 Beirut</strong><br>
  A foundational C library built from scratch, designed for reusability, robustness, and performance.
</p>

---

## 📌 Project Description

**Libft** is a personal implementation of essential C standard library functions, developed as the first project in the 42 curriculum. This library is designed to be reused across future C projects and strictly follows memory safety and coding standards.

This version includes both **mandatory** and **bonus** functions, offering full support for core utilities and singly linked list management.

---

## 📁 Project Structure

```
libft/
├── ft_*.c        # Implementation of all required and bonus functions
├── libft.h       # Header file containing function prototypes and the t_list structure
├── Makefile      # Build script with standard rules (all, clean, fclean, re, bonus)
```

---

## ✅ Implemented Functions

### 🔹 Part 1: Libc Functions

- Character checks: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- Memory operations: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`
- String operations: `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`
- Case conversion: `ft_toupper`, `ft_tolower`
- Conversion: `ft_atoi`
- Allocation: `ft_calloc`

### 🔹 Part 2: Additional Functions

- String utilities: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
- Conversion: `ft_itoa`
- String iteration: `ft_strmapi`, `ft_striteri`
- Output: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### 🔸 Bonus Part: Linked List Functions

- Creation: `ft_lstnew`
- Insertion: `ft_lstadd_front`, `ft_lstadd_back`
- Traversal & Query: `ft_lstsize`, `ft_lstlast`, `ft_lstiter`
- Mapping & Cleanup: `ft_lstdelone`, `ft_lstclear`, `ft_lstmap`

---

## 🧪 Compilation

```bash
make         # Builds libft.a
make clean   # Removes object files
make fclean  # Removes object files and libft.a
make re      # Cleans and rebuilds everything
make bonus   # Builds with bonus part (linked list)
```
