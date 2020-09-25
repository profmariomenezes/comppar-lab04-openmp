# comppar-lab04-openmp
Repositório para as atividades de programação OpenMP - 

## Ativ. Prog 04 - Avaliação de desempenho

### Somatório de números

Faça um programa que some todos os números de um vetor de tamanho $2^{30}$. Garanta que os números neste vetor sejam sempre os mesmos para garantir o mesmo resultado final!

Construa 2 versões em paralelo utilizando #pragma omp for que soma parcialmente os valores e:

    que utiliza uma variável compartilhada e #pragma omp critial para controle de seção crítica
    que utiliza #pragma omp ... reduction(...) para a somatória final

Faça uma comparação de tempo de execução com 1, 2, 3, 4, 5 e 6 threads, para cada versão. Construa uma tabela contendo o tempo médio de 10 execuções para cada versão e sua respectiva quantidade de threads.

Faça um gráfico que mostre a escalabilidade forte (mínimo de $2^{28}$, com garantia de todos os dados em memória) e escalabilidade fraca (use $2^{30}$ como quantidade máxima de dados) do Speedup para cada quantidade de threads utilizada.

Entregue os códigos fontes e as tabelas no formato Excel, onde cada aba da planilha é relativa a uma versão diferente de código com sua respectiva tabela de execução e seu respectivo gráfico de speedup.

## Ativ. Prog. 05 - Nova multiplicação de matrizes

Faça um programa de multiplicação de matrizes. Fique atento a um bom uso de cache (L1/L2)

Construa uma versão sequencial e uma versão paralela com OpenMP, utilizando alguma das técnicas estududas e/ou apresentadas na literatura.

Faça uma comparação de tempo de execução com 1, 2, 3, 4, 5 e 6 threads, para cada versão. Construa uma tabela contendo o tempo médio de 3 execuções para cada versão e sua respectiva quantidade de threads.

Faça um gráfico que mostre a escalabilidade do Speedup para cada quantidade de threads utilizada.

Entregue os códigos fontes e as tabelas no formato Excel, onde cada aba da planilha é relativa a uma versão diferente de código com sua respectiva tabela de execução .

**Tarefa em dupla.**
