## Autores

- João Pedro Sousa Bianchim (R.A: 11201920729)
- João Pedro Corrêa Silva   (R.A: 11202321629)

## Como Compilar e Executar:
Por praticidade há a pasta inputs com arquivos que podem ser usados para validar o programa (há os arquivos de exemplo do professor e outros criados com o generator fornecido)

### Código Sequencial
Para Compillar:
`gcc -o programa_sequencial projeto-seq.c `

Para executar:
`./programa_sequencial < inputs/06.in`


### Código Paralelo

Para Compilar:
`mpicc -o projeto_paralelo projeto-paralelo-final.c`



Para executar:
`mpirun -np 9 ./projeto_paralelo < inputs/06.in`

**Instruções da execução**: é necessário rodar com o número de processadores (número logo após -np) sendo um número entre 2 e 9.