# 💸 Aplicativo de Controle de Transações Financeiras - Java POO

Este projeto é um aplicativo simples de controle de transações financeiras pessoais, desenvolvido com os princípios da **Programação Orientada a Objetos (POO)** em **Java**. O objetivo é registrar, listar e categorizar entradas e saídas financeiras, permitindo uma melhor organização das finanças pessoais.

---

## 🧠 Conceitos Utilizados

- Programação Orientada a Objetos (POO)
  - Encapsulamento
  - Herança (se aplicável)
  - Polimorfismo
  - Abstração
- Manipulação de Listas e Datas
- Interação com o usuário via console
- Boas práticas de estruturação de código

---

## 🛠️ Tecnologias e Ferramentas

- **Java 17+**
- IDE recomendada: IntelliJ IDEA, Eclipse ou VS Code
- JDK instalado

---

## 📦 Estrutura do Projeto

```bash
src/
├── Main.java
├── model/
│   ├── Transacao.java
│   ├── TransacaoEntrada.java
│   └── TransacaoSaida.java
├── service/
│   └── GerenciadorFinanceiro.java
└── util/
    └── Menu.java

📋 Funcionalidades

    ✅ Cadastro de transações (entrada ou saída)

    ✅ Classificação por categorias (Ex: Alimentação, Salário, Transporte)

    ✅ Listagem de todas as transações

    ✅ Cálculo de saldo total

    ✅ Filtros por tipo ou categoria

🧱 Classes Principais
Transacao (Classe Abstrata)

    id: int

    descricao: String

    valor: double

    data: LocalDate

    categoria: String

TransacaoEntrada & TransacaoSaida (Herdam de Transacao)

    Representam os dois tipos principais de movimentação financeira.

GerenciadorFinanceiro

    Responsável por armazenar, listar e calcular saldo das transações.

Menu

    Exibe o menu de opções e lida com a entrada do usuário.

▶️ Como Executar

    Clone este repositório:

git clone https://github.com/seu-usuario/controle-financeiro-java.git

    Compile os arquivos Java:

javac src/**/*.java

    Execute o programa:

java src/Main

✏️ Exemplo de Uso

===== MENU FINANCEIRO =====
1. Adicionar Transação
2. Listar Transações
3. Ver Saldo Atual
4. Filtrar por Categoria
5. Sair
Escolha: 1

Tipo de Transação (1-Entrada | 2-Saída): 1
Descrição: Salário
Valor: 3000
Categoria: Trabalho
Data (AAAA-MM-DD): 2025-07-18
Transação adicionada com sucesso!

📚 Aprendizados

Este projeto foi idealizado para aplicar os pilares da Programação Orientada a Objetos na prática. Além disso, permite que você:

    Melhore suas habilidades com Java puro

    Pratique modelagem de classes e separação de responsabilidades

    Desenvolva a lógica de negócios de um sistema realista

🚀 Possíveis Melhorias Futuras

    Interface gráfica com JavaFX ou Swing

    Persistência em arquivo ou banco de dados

    Exportação de relatórios em PDF ou CSV

    Autenticação de usuários

