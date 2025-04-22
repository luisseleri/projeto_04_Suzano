# projeto_04_Suzano

Este projeto é um sistema bancário simples desenvolvido em Python, utilizando conceitos de POO (Programação Orientada a Objetos). A aplicação roda no terminal e permite operações como criação de contas, depósitos, saques e visualização de extratos.

🚀 Funcionalidades
📄 Cadastro de clientes (Pessoa Física)

🏦 Criação de contas bancárias (Conta Corrente)

💸 Depósito em conta

🏧 Saque com regras de limite por valor e quantidade

📊 Consulta de extrato da conta

📃 Listagem de todas as contas criadas

🧱 Estrutura do Projeto
Cliente: Classe base para clientes, com gerenciamento de contas.

PessoaFisica: Subclasse de Cliente, contendo nome, CPF e data de nascimento.

Conta: Classe base para contas bancárias, com métodos de saque, depósito e histórico.

ContaCorrente: Subclasse de Conta com limite de saque por valor e quantidade.

Historico: Registra todas as transações (depósitos e saques) realizadas na conta.

Transacao: Classe abstrata para representar operações bancárias.

Saque e Deposito: Subclasses de Transacao que executam operações específicas.

Funções auxiliares para interações com o usuário (menu, extrato, criação de conta/cliente).

⚙️ Como executar
Certifique-se de ter o Python 3 instalado.

Clone o repositório ou copie os arquivos para seu ambiente local.

Execute o script:

bash
Copiar
Editar
python sistema_bancario.py
Utilize o menu exibido no terminal para navegar entre as opções.

📌 Exemplo de uso
bash
Copiar
Editar
=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> d
Informe o CPF do cliente: 12345678900
Informe o valor do depósito: 100
=== Depósito realizado com sucesso! ===
📚 Conceitos aplicados
Programação Orientada a Objetos

Herança e Polimorfismo

Classes Abstratas com abc

Encapsulamento

Manipulação de listas e entrada de dados

Boas práticas de código limpo

🛠️ Melhorias futuras
Armazenamento em arquivo ou banco de dados

Interface gráfica com Tkinter ou PyQt

Geração de relatórios em PDF

Integração com sistema de autenticação

📄 Licença
Este projeto está sob a licença MIT. Fique à vontade para usar, modificar e distribuir.
