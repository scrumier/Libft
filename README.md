# Libft - Custom Standard Library 🛠️

Welcome to **Libft**, my custom implementation of essential C library functions. This project, a staple for students at **École 42**, is designed to deepen my understanding of low-level programming and the inner workings of commonly used C functions.

## 📖 About Libft
Libft is a personal library that reimplements functions from the standard C library (like `libc`). By recreating these foundational functions, I’ve gained insight into memory management, string manipulation, and data structures. It’s a project that emphasizes meticulous coding practices and optimized performance.

## 🚀 Key Features
Libft is divided into several sections, each with its own focus:

### Part 1: Standard C Library Functions
Reimplementations of functions such as:
- **String Manipulation**: `ft_strlen`, `ft_strcpy`, `ft_strncmp`, etc.
- **Memory Functions**: `ft_memset`, `ft_memcpy`, `ft_memmove`, etc.
- **Character Checks**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, etc.

### Part 2: Additional Utility Functions
Extensions to the standard functions that provide additional functionality, such as:
- **String Joining and Slicing**: `ft_substr`, `ft_strjoin`, `ft_split`, etc.
- **Conversion Functions**: `ft_itoa`, `ft_atoi`, etc.

### Part 3: Linked List Functions
Basic linked list management functions, which introduce data structures:
- **Linked List Manipulation**: `ft_lstnew`, `ft_lstadd_front`, `ft_lstiter`, etc.

### Part 4: Bonus Functions
Additional functions that provide more utility and enhance the versatility of Libft.

## 🔧 Compilation
To compile the library, simply run:
```bash
make
```
This will generate a `libft.a` file, which can be linked with other C projects to provide the custom functions.

## 📝 Usage
After compilation, you can link `libft.a` in your own projects:
```c
gcc my_program.c -L. -lft -o my_program
```

## 🌱 Learning Outcomes
Building Libft has strengthened my understanding of memory allocation, pointer manipulation, and C’s standard library structure. It’s been a fantastic foundation for more complex projects.

## 🤝 Contributing
Libft was designed as a solo project, but I’m always open to ideas or improvements! If you have suggestions, feel free to reach out.

## 🔗 Connect with Me
For collaboration or if you’re interested in this project, connect with me on [LinkedIn](https://www.linkedin.com/in/sonam-crumiere/).

Happy coding!
