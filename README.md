# Prova 1 de Sistemas Distribuidos

Nome: Luis Felipe Cardoso
RA: FO352a9b57c8aa4c9492

## Problema da empresa

A empresa precisa informar o estoque do produto da empresa fazendo a conta de saldo inicial - o saldo que vendeu

## Arquivos

- servidor.py: recebe a chamada RPC e executa o cálculo.
- cliente.py: solicita o cálculo ao servidor e mostra a resposta.

## Resultado do teste

PS C:\Users\aluno\Desktop>  & 'C:\Program Files\Python313\python.exe' 'c:\Users\aluno\.vscode\extensions\ms-python.debugpy-2026.6.0-win32-x64\bundled\libs\debugpy\launcher' '55414' '--' 'c:\Users\aluno\Desktop\cliente.py' 
Unidades restantes: 11

## Explicação 

1. Em qual programa o cálculo foi executado?
   Servidor

2. Qual programa iniciou a solicitação?
   Cliente

3. O que aconteceria com o cliente se o servidor estivesse desligado?
   Daria um erro e não sairia nenhum resultado, pois o calculo só está no servidor.
