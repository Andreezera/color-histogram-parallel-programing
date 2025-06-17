# color-histogram-parallel-programing
Desafio de conversão de código sequencial para paralelo para a disciplina de "Introdução à Programação Paralela e Distribuída"

Problema: Color Histogram


gcc color-histogram-sequencial.c -o hist_seq

./hist_seq < imagem.ppm


gcc color-histogram-parallel.c -fopenmp -lm -o hist_omp

./hist_omp < imagem.ppm
