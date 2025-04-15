![libft github header](https://github.com/user-attachments/assets/0fb5c62d-d009-40f4-a447-117ccb833e44)
# 📚 Libft – 42 Project

## 🗂️ Table of Contents

- [What is it?](#what-is-it)

- [Features](#features)

- [Installation](#installation)

- [Usage](#usage)

- [License](#license)

- [Author](#author)
---

### What is it? <a id="what-is-it"></a>
The libft project is a custom implementation of essential C Standard Library functions, developed as part of the 42 School curriculum. It serves as the ground level for code interpretation of basic functions, memory management and overall low-level programming in C.

---

### ✨ Features <a id="features"></a>
- ✅ Implements replicated functions of the stardard C library.
- ✅ Includes extra functions on string manipulation, memory management and linked lists.
- ✅ Streamlines the importing process as a helper library for future projects.
- ✅ Easy and flexible updates for future added functions.

---

### 📥 Installation <a id="installation"></a>
Clone this repository:
```
git clone https://github.com/whtifigo/42_Libft.git
```
Change your current path to the ```42_Libft``` folder:
```
cd 42_Libft
```
Access the ```libft``` folder directly:
```
cd libft
```
And compile everything:
```
make
```
Having done this, a ```libft.a``` will be created!

---

### ⚙️ Usage <a id="usage"></a>
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
_I've compiled it with:_
```
cc -Wall -Wextra -Werror
```

---

### 📜 License <a id="license"></a>

This repository was granted permission and is licensed under the **MIT License**

---

### 👤 Author <a id="author"></a>

@ WHTIFIGO

