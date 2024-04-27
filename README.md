## Travelling Salesman Problem using Genetic algorithm and OpenMP

## Compiling and Running

```bash
gcc parallel.c -o parallel -fopenmp -lm
./parallel <input>
```

```bash
gcc serial.c -o serial -lm
./serial <input>
```