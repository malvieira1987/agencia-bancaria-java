# 🏦 Agência Bancária em Java

Este é um projeto simples de terminal para simular o funcionamento de uma **agência bancária**, permitindo criação de contas, depósitos, saques, 
transferências e listagem de contas. O sistema utiliza conceitos de orientação a objetos em Java.

## ✨ Funcionalidades

- Criar contas bancárias (Corrente ou Poupança)
- Depositar dinheiro em uma conta
- Sacar dinheiro de uma conta
- Transferir dinheiro entre contas
- Realizar transferências via PIX (usando CPF)
- Listar todas as contas, somente contas correntes ou poupança
- Menu interativo no terminal

## 📁 Estrutura do Projeto

src/
├── main/
│ ├── AgenciaBancaria.java # Classe principal com a interface e lógica do sistema
│
└── model/
├── Pessoa.java # Representa um cliente
├── Conta.java # Classe abstrata com atributos comuns das contas
├── ContaCorrente.java # Subclasse representando conta corrente
├── ContaPoupanca.java # Subclasse representando conta poupança

bash
Copiar
Editar

## 🛠️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/agencia-bancaria-java.git
Compile o projeto:

bash
Copiar
Editar
javac main/AgenciaBancaria.java model/*.java
Execute:

bash
Copiar
Editar
java main.AgenciaBancaria
Obs: Verifique se o seu terminal está na raiz correta onde o projeto foi clonado.

💡 Tecnologias Utilizadas
Java (JDK 8+)

Paradigma de Programação Orientado a Objetos

Scanner para entrada de dados via terminal

📌 Exemplos de Uso
plaintext
Copiar
Editar
------------------------------------------------------
-------------Bem vindos a nossa Agência---------------
------------------------------------------------------
***** Selecione uma operação que deseja realizar *****
------------------------------------------------------
|   Opção 1 - Criar conta          |
|   Opção 2 - Depositar            |
|   Opção 3 - Sacar                |
|   Opção 4 - Transferir           |
|   Opção 5 - Pix                  |
|   Opção 6 - Listar               |
|   Opção 7 - Sair                 |
------------------------------------------------------
