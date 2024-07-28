# Implementation of Smith-Waterman Algorithm in SIMT using CUDA
Submitted by:  
Ambrosio, Carlos Felipe Quitara  
Arceta, Althea Zyrie Manuel  
Mendoza, Antonio Gabriel Notario  
Tan, Jose Tristan Turtoza  

This project aims to improve the computational efficiency of the Smith-Waterman algorithm for local protein sequence alignment by taking advantage of CUDA's parallel computing capabilities. The algorithm will be implemented in both sequential C and parallelized CUDA versions, focusing on optimizing the scoring phase utilizing the BLOSUM62 substitution matrix and affine gap penalties. Following this, the performance of both versions will be evaluated by comparing execution times and confirming the CUDA implementation. The purpose is to demonstrate that GPU acceleration may dramatically reduce execution time, highlighting its potential for improving computationally complicated bioinformatics algorithms.
