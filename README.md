# 💰 Aplicativo de Controle de Transações Financeiras com POO

Este é um projeto Java desenvolvido para consolidar os fundamentos da **Programação Orientada a Objetos (POO)**, simulando operações bancárias básicas como criação de contas, depósitos, saques, transferências via PIX, investimentos e consulta de histórico de transações.

---

## 🎯 Objetivos do Projeto

- Praticar conceitos de **encapsulamento**, **herança**, **polimorfismo** e **abstração**
- Criar um sistema modular e extensível usando boas práticas de design
- Simular um ambiente bancário seguro e funcional usando Java puro

---

## 🛠️ Tecnologias Utilizadas

- **Java 17+**
- **POO (Programação Orientada a Objetos)**
- `BigDecimal`, `LocalDateTime`, `List<>`, `Scanner`, etc.

---

## 📦 Estrutura de Pacotes

src/ ├── app/ # Entrada principal (Main) ├── model/ # Domínio (User, Account, PixAccount, etc.) ├── service/ # Regras de negócio ├── repository/ # Simulação de persistência └── util/ # Ferramentas auxiliares (validações, formatadores)


---

## 📂 Principais Classes

| Classe            | Papel                                              |
|-------------------|----------------------------------------------------|
| `User`            | Representa um usuário e suas contas                |
| `Account`         | Abstração de uma conta bancária                    |
| `PixAccount`      | Conta com operações de transferência via Pix       |
| `InvestmentAccount`| Conta voltada para aplicações financeiras         |
| `Transaction`     | Registra movimentações bancárias                   |

---

## 📄 Funcionalidades

- ✅ Criar usuários e contas
- ✅ Depositar e sacar valores
- ✅ Transferir via PIX entre contas
- ✅ Aplicar em investimentos
- ✅ Consultar histórico de transações
- ✅ Interface simples via terminal (CLI)

---

## 📋 Exemplo de Execução

```bash
Bem-vindo ao Sistema Bancário 💳

1 - Criar Conta
2 - Realizar Depósito
3 - Realizar Saque
4 - Transferência PIX
5 - Investir
6 - Ver Histórico
0 - Sair
🧪 Testes
Os testes podem ser incluídos futuramente com JUnit para validar regras de negócio, como:

Transferência sem saldo

Validação de CPF

Rendimento de investimentos

📝 Autor
Diego Spadotto 📍 Botucatu - SP 🔗 GitHub Profile 📧 Em construção...

📄 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar, modificar e contribuir!
