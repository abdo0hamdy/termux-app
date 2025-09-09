# Termux + Hello World (C/C++)

This repository is a fork of the [Termux app](https://github.com/termux/termux-app), extended with a simple **Hello World** program written in C/C++ as part of a software development internship task.
---

## 📌 Setup Instructions

pkg update && pkg upgrade -y
pkg install clang -y

then add the code.cpp : 
#include <stdio.h>
int main() {
printf("Hello, World!\n");
return 0;
} 
CTRL + o => Enter => CTRL + x 
then create a file to compile 
clang++ task.cpp -o task => ./task
# Expected output: Hello, World!
