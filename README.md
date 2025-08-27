# Desafio de Controle de Fluxo – DIO

Repositório destinado ao desafio de controle de fluxo (loops, condicionais e tratamento de exceções) proposto pela Digital Innovation One (DIO).

---

##  Licença

Este projeto está licenciado sob a **MIT License**. Caso deseje mais informações, confira o arquivo `LICENSE` incluído no repositório.

---

##  Descrição do Desafio

Desenvolva um programa em Java que execute uma contagem e exiba os números de forma sequencial entre dois parâmetros inteiros informados pelo usuário. O sistema deve aplicar lógica de controle de fluxo (laços `for`, condicionais) e tratamento de erros com exceção customizada.

---

##  Requisitos Funcionais

1. O programa deve solicitar ao usuário dois valores inteiros via terminal:
   - **Parâmetro 1**: valor inicial
   - **Parâmetro 2**: valor final
2. Se o **parâmetro 1** for maior que o **parâmetro 2**, deve ser lançada uma exceção customizada:
   - Classe: `ParametrosInvalidosException`
   - Mensagem: "O segundo parâmetro deve ser maior que o primeiro"
3. Se os parâmetros forem válidos, o programa executa um laço de contagem do `parâmetro 1` até o `parâmetro 2`, imprimindo cada número na saída padrão.
