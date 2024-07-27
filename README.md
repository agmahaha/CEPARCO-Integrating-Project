# Implementation of Smith-Waterman Algorithm in SIMT using CUDA
Submitted by:
Ambrosio, Carlos Felipe Q.
Arceta, Althea Zyrie Manuel
Mendoza, Antonio Gabriel Notario
Tan, Jose Tristan Turtoza

This project aims to improve the computational efficiency of the Smith-Waterman algorithm for local protein sequence alignment by taking advantage of CUDA's parallel computing capabilities. The algorithm will be implemented in both sequential C and parallelized CUDA versions, focusing on optimizing the scoring phase utilizing the BLOSUM62 substitution matrix and affine gap penalties. Following this, the performance of both versions will be evaluated by comparing execution times and confirming the CUDA implementation. The purpose is to demonstrate that GPU acceleration may dramatically reduce execution time, highlighting its potential for improving computationally complicated bioinformatics algorithms.

## Discussion of Parallel Algorithm Implemented
The following were parallelized using CUDA
a.) Scoring Matrix
b.) Traceback

## Performance Comparison
Both implementations are run *n* times, and the average runtime is calculated. Below are the tables showing the average runtime of both implementations.

| Array Size | C | CUDA | Speedup |
| ------------- |-------------|------------- |------------- |
| 2^4 | 2.299107 ms | 140.978020 ms | 2257.447447 ms |
| 2^8 | 8.670397 ms | 541.459027 ms | 8749.174177 ms |

## Analysis

