# Projeto da Software

Autor: Nelson S. dos Santos
Data: 13/12/2023
Revisor: 

## Introdução

## Projeto de arquitetura

A aplicação deverá ter os seguintes módulos

1. Módulo de entrada e saída
Este módulo oferecerá as seguintes funções:

- função de leitura do teclado para escolha da pasta de gravação na primeira iniciação do sistema - leitor_pasta()
- função de leitura das ações para estimação do CAPM - leitor_acoes()
- função de leitura de preços de ações - leitor_precos()
- função de escrita de arquivo csv - grava_arquivo()

## Projeto de estruturas de dados

- O código B3 das ações deverão ser guardadas em listas.
- A pasta de gravação deverá ser guardada em um string.
- Os preços das ações deverão ser guardados em um array.

## Projeto de algoritmos

Aqui colocaremos apenas a assinatura das funções deixando ao desenvolvedor a escolha do algoritmo ótimo.

- leitor_pasta() -> string
- leitor_acoes() -> lista
- leitor_precos() -> array
- grava_arquivo(var: objetoArquivo) -> Null

