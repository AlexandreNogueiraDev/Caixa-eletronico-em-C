💰 Sistema de Caixa Eletrônico em C

Projeto desenvolvido em linguagem C que simula o funcionamento de um caixa eletrônico, permitindo realizar saques, controlar o saldo, gerenciar a quantidade de notas disponíveis e gerar recibos.

🚀 Funcionalidades
Realização de saques.
Verificação de saldo disponível.
Controle da quantidade de notas no caixa.
Distribuição automática de notas.
Validação dos valores de saque.
Geração e armazenamento de recibos em arquivo .txt.
Persistência do saldo e das notas disponíveis entre execuções.
💵 Notas disponíveis

O caixa trabalha com as seguintes cédulas:

R$ 100
R$ 50
R$ 20
R$ 10
R$ 5
🛠️ Tecnologias utilizadas
Linguagem C
Biblioteca stdio.h
Biblioteca string.h
Manipulação de arquivos (fopen, fprintf, fscanf e fgets).
📂 Arquivos gerados
Arquivo	Descrição
caixa.txt	Armazena o saldo e a quantidade de notas disponíveis.
recibo.txt	Armazena o histórico de saques realizados.
▶️ Como executar
Clone o repositório:
bash
git clone URL_DO_SEU_REPOSITORIO

Entre na pasta do projeto:
bash
cd nome-do-projeto

Compile o programa:
bash
gcc main.c -o caixa

Execute:
bash
./caixa


No Windows:

bash
caixa.exe

📚 Objetivo do projeto

Praticar conceitos fundamentais da linguagem C, como:

Estruturas de repetição e decisão.
Arrays e manipulação de variáveis.
Funções de entrada e saída.
Manipulação de arquivos.
Validação de dados.
Lógica de programação.
🔮 Melhorias futuras
Implementar um menu de operações.
Permitir adicionar notas ao caixa.
Criar um histórico de transações mais completo.
Melhorar o tratamento de erros na manipulação de arquivos.

Desenvolvido como projeto de estudo em linguagem C.
