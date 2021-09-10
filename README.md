# Jetson TK1 CUDA Learn
- Building script
```
nvcc <FILE_NAME>.cu -o <FILE_NAME> -lcuda
```
- Run profilling using `nvprof`,
```
nvprof --unified-memory-profiling off ./<FILE_NAME>
```