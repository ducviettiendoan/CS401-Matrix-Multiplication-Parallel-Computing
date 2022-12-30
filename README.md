# CS401-Matrix-Multiplication-Parallel-Computing
__Author__: Khoi Le and Duc Doan

__*GOAL*__: To discover matrix multiplication algorithms and implement them in parallel to see + compare the runtime and overheads each algorithm has. The improvement in runtime is made in comparing to the naive O(n^3) sequential algorithm. We also care about the cache friendly as a factor with more details in the SUMMA Algorithm. 

Compile code (-pthread for pthread and -fopenmp for openMP):
```
g++ -pthread summa.cpp -fopenmp -o summa
```
Link to the research paper: https://online.flippingbook.com/view/87471271/
