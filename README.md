# 📚 Libft – 42 Project

## 🗂️ Table of Contents

- <a href="#what-is-it">What is it?</a>

- <a href="#-features">Features</a>

- <a href="#-installation">Installation</a>

- <a href="#-usage">Usage</a>

- <a href="#-license">License</a>

👤 Author
### What is it?
The libft project is custom implementation of essential C Standard Library functions, developed as part of the 42 School curriculum. It serves as the ground level for code interpretation of basic functions, memory management and overall low-level programming in C.

### ✨ Features
- ✅ Implements replicated functions of the stardard C library.
- ✅ Includes extra functions on string manipulation, memory management and linked lists.
- ✅ Streamlines the importing process as a helper library for future projects.
- ✅ Easy and flexible updates for future added functions.

### 📥 Installation
Clone this repository:
```
git clone https://github.com/whtifigo/42_Libft.git
```
Change your current path to the ```42_Libft``` folder:
```
cd 42_Libft
```
And compile everything:
```
make
```
Having done this, a ```libft.a``` will be created!

### ⚙️ Usage
Include the ```libft.h``` anywhere in your project:
```
#include "libft.h"
#include <stdio.h>

int main(void)
{
    char *copy = ft_strdup("Libft is awesome!");
    printf("%s\n", copy);
    return 0;
}
```
I've compiled it with:
```
cc -Wall -Wextra -Werror
```
### 📜 License


