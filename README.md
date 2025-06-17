# color-histogram-parallel-programing
Desafio de conversão de código sequencial para paralelo para a disciplina de "Introdução à Programação Paralela e Distribuída"


### Problema: Color Histogram
O problema consiste em calcular o histograma de cores de uma imagem no formato PPM

## Como rodar:

### Código Sequencial

**Compilação:**
```bash
gcc color-histogram-sequencial.c -o hist_seq
```
**Execução:**
```bash
./hist_seq < imagem.ppm
```
---

### Código Paralela (OpenMP)

**Compilação:**
```bash
gcc color-histogram-parallel.c -fopenmp -lm -o hist_omp
```

**Execução:**
```bash
./hist_omp < imagem.ppm
```
