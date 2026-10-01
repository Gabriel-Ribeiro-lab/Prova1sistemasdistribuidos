Prova 1 de Sistemas Distribuidos

Gabriel Ribeiro de Oliveira
RA: a4dcc893a8bccc18b920

## Problema da Empresa

o cliente quer saber quantos pontos faz com uma compra de 120 reais, solicita o resultado ao servidor.

## Arquivos
- servidor.py: recebe a chamada RPC e executa o calculo.
- cliente.py: solicita o calculo ao servidor e mostra a resposta.

## Resultado do teste


PS C:\Users\aluno\Desktop> python cliente.py
Pontoss: 240
PS C:\Users\aluno\Desktop>

## explicação

1- Em qual programa o cálculo foi executado?

R: No servidor (servidor.py), que é onde fica a função que faz a conta.

2 -Qual programa iniciou a solicitação?

R: O cliente (cliente.py) foi quem pediu o cálculo.

3- O que aconteceria se o servidor estivesse desligado?

R: O cliente não conseguiria se conectar e daria um erro de conexão.
