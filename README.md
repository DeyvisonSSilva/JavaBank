# 💳 Sistema Bancário em Java - POO

Desenvolvido como um desafio para o Bootcamp da NTTDATA 2025 pela DIO. Este projeto é uma aplicação Java orientada a objetos, desenvolvida com o objetivo de consolidar os principais conceitos da **Programação Orientada a Objetos (POO)**, como **herança**, **encapsulamento**, **polimorfismo**, **abstração** e **reuso de código**.

## 🧠 Objetivo

A aplicação tem como finalidade oferecer uma base sólida no desenvolvimento com Java, por meio da simulação de um **sistema bancário básico**, permitindo praticar e demonstrar a aplicação dos pilares da POO em um cenário realista.

## 🛠️ Tecnologias Utilizadas

- Java (versão 17 ou superior)
- Paradigma de Programação Orientada a Objetos
- Java Collections API
- `java.time` para manipulação de datas
- Estrutura de dados como `List`, `Map`, `Set`

## ⚙️ Funcionalidades Implementadas

- ✅ Criação de contas bancárias com chave PIX
- ✅ Depósitos e saques
- ✅ Transferências via PIX entre contas
- ✅ Criação e simulação de investimentos
- ✅ Histórico completo de transações (MoneyAudit)
- ✅ Agrupamento e visualização por data
- ✅ Tratamento de exceções específicas (como conta inexistente ou saldo insuficiente)

## 🧩 Conceitos de POO Aplicados

| Conceito        | Implementação                                                              |
|----------------|----------------------------------------------------------------------------|
| **Herança**     | Superclasse `Account` com subclasses especializadas                       |
| **Encapsulamento** | Atributos privados com acesso via getters/setters                      |
| **Polimorfismo** | Sobrecarga e sobrescrita de métodos em diferentes tipos de contas        |
| **Abstração**    | Métodos abstratos definidos em classes base para padronizar comportamento |
| **Reuso de Código** | Uso de interfaces e classes utilitárias para evitar duplicação        |

## 🧪 Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/DeyvisonSSilva/JavaBank.git
   cd JavaBank
   
2. Compile e execute com uma IDE (como IntelliJ ou Eclipse) ou via terminal:

   javac -d bin src/**/*.java  
   java -cp bin Main
   
(Obs.: O projeto não utiliza frameworks externos, sendo 100% baseado na JDK.)

## 🗃️ Estrutura do Projeto

```
src/  
└── main/  
    └──  
        ├── exception/  
        │   └── [classes de exceção].java  
        │  
        ├── model/  
        │   ├── AccountWallet.java  
        │   ├── BankService.java  
        │   ├── Investment.java  
        │   ├── InvestmentWallet.java  
        │   ├── Money.java  
        │   ├── MoneyAudit.java  
        │   └── Wallet.java  
        │  
        ├── repository/  
        │   ├── AccountRepository.java  
        │   ├── CommonsRepository.java  
        │   └── InvestmentRepository.java  
        │  
        └── Main.java
```
