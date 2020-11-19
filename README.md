# Parallel_Compute_C
using C  language to write parallel program




## Before Parallel Learning
Parallel Computing is based on Serial Computing. Before your start, some programing fundation is needed.

Here, we provide some code of C language, to help you start.

# Serial C program, compile and run like this:
```bash
gcc -o hello  hello_world.c
./hello
```

# Parallel C program with mpi, compile and run like this:
```bash
mpicc -g -Wall -o multi_hello multi_hello.c 
mpiexec -n 4 ./multi_hello
```