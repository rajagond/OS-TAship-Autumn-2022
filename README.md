# OS-TAship-Autumn-2022

## Course ( CS 347 / CS 333)
Instructors
- [Prof. Purushottam(Puru) Kulkarni](https://www.cse.iitb.ac.in/~puru/)
- [Prof. Umesh Bellur](https://www.cse.iitb.ac.in/~umesh/)

Course Webpage:
- [CS 347/CS 333](https://www.cse.iitb.ac.in/~puru/courses/autumn2022/index.html)

### Xv6 Installation
  
Follow the instructions given [here](https://github.com/cserl-iitb/bootcamp2022/blob/main/week1_warmup/xv6_Installation/README.md) for xv6 installation. xv6 runs on an x86 emulator called QEMU that emulates x86 hardware on your local machine. In the xv6 folder, run the following command sequence ..
```bash
make
make qemu or make-qemu-nox
```
to boot xv6 and open a shell.

I. At the shell try out a few shell commands starting with ls to find a list of available programs and then try
and execute a few of them.

II. Look up the implementation of these programs. For example, `cat.c` is the source code for the cat
program. Execute and lookup the following: `ls, cat, wc, echo, grep` etc. Understand how the syntax in some
places is different from normal C syntax.

III. Check the makefile to see how the program wc is set up for compilation.
`make qemu`

Build everything and start qemu with the VGA console in a new window and the serial console in your terminal. To
exit, either close the VGA window or press Ctrl-c or Ctrl-a x in your terminal.
`make qemu-nox`
Like make qemu, but run with only the serial console. To exit, press `Ctrl-a x`. This is particularly useful over SSH
connections.

### Labs
- [Lab 3](lab3/lab3.pdf)
- [Lab 5](lab5/lab5.pdf)
- [Lab 6](lab6/lab6.pdf)

Note: All other labs and lab quizzes can be found [here](https://www.cse.iitb.ac.in/~puru/courses/autumn2022/labs.html)

### Notes
- [Notes](CS347Notes/notes.pdf)

Note: class notes can be found [here](https://www.cse.iitb.ac.in/~puru/courses/autumn2022/schedule.html)

### Other Resources
- [xv6 Book](https://pdos.csail.mit.edu/6.828/2018/xv6/book-rev10.pdf)
- [Prof. Mythili Vutukuru's OS Course](https://www.cse.iitb.ac.in/~mythili/os/)