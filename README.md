
~/ $ mkdir ~/pset1/
~/ $ cd ~/pset1/
~/pset1/ $ mkdir ~/pset1/hello
~/pset1/ $ cd ~/pset1/hello
~/pset1/hello/ $ ls
hello.c
~/pset1/hello/ $ clang hello.c
~/pset1/hello/ $ ls
a.out*  hello.c
~/pset1/hello/ $ ./a.out
hello, world
~/pset1/hello/ $ clang -o hello hello.c
~/pset1/hello/ $ ls
a.out*  hello*  hello.c
~/pset1/hello/ $ ./hello
hello, world
~/pset1/hello/ $ make hello
clang -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
~/pset1/hello/ $ ./hello
hello, world
~/pset1/hello/ $ 



