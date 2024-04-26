# program-optimization-openmp
The objective of this work is to use the OpenMP library to parallelize a sequential algorithm and verify the time savings when executing both codes on the same machine.

# Enviroment
- GCC - Version 13.2.0

# Compiling codes
```console
gcc esparso_seq.c -fopenmp -o esparso_seq -Wall
```

```console
gcc esparso_par.c -fopenmp -o esparso_par -Wall
```
