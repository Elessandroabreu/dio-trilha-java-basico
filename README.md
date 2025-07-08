Projeto: Conta Terminal
Este projeto simula a criação de uma conta bancária através do terminal (linha de comando), utilizando a linguagem Java e a classe Scanner para entrada de dados do usuário.

Objetivo
O objetivo principal deste exercício é praticar:

Entrada de dados com a classe Scanner;

Manipulação de tipos primitivos em Java (int, double, String);

Uso do método printf para exibir uma mensagem formatada;

Estrutura básica de um programa Java com main.

Como funciona
O programa solicita ao usuário que informe:

O nome da agência;

O número da conta;

O nome do cliente;

O saldo da conta.

Após o preenchimento das informações, o sistema exibe uma mensagem personalizada com os dados da conta criada.

💻 Exemplo de uso no terminal
yaml
Copiar
Editar
Digite o nome da Agencia: 
1234-5
Digite o numero da conta: 
67890
Digite o nome do Cliente: 
João Silva
Digite o Saldo da conta: 
2500.75

Saída esperada:



Olá João Silva, obrigado por criar uma conta em nosso banco, sua agência é 1234-5, conta 67890 e seu saldo 2500.750000, já está disponível para saque

Observação:
O número de casas decimais pode ser ajustado com %.2f no printf, caso prefira formatar o saldo com duas casas:


System.out.printf("... saldo %.2f ...", saldo);
