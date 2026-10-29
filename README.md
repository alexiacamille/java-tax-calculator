# 🧮 Calculadora de Impostos em Java

Uma aplicação desenvolvida em Java projetada para calcular os impostos de contribuintes, diferenciando as regras fiscais aplicadas a pessoas físicas e pessoas jurídicas. 

O principal objetivo deste projeto foi aplicar e consolidar os pilares da **Programação Orientada a Objetos (POO)** na linguagem Java.

  Tecnologias Utilizadas:

* **Java** (Linguagem principal)
* **Git & GitHub** (Controle de versão e hospedagem)

## Conceitos de POO Aplicados

Para resolver o problema de cálculo de diferentes tipos de impostos, a estrutura do código utiliza:

 **Abstração**: Criação de uma classe abstrata molde para representar um contribuinte genérico.
 **Herança:** Classes específicas para Pessoas Físicas e Pessoas Jurídicas que herdam as características da classe mãe.
* **Polimorfismo:** Uso de métodos sobrepostos para calcular o imposto de formas totalmente diferentes, dependendo do tipo de contribuinte.

## Como Funciona a Regra de Negócio:

 **Pessoa Física:** O cálculo do imposto varia conforme a renda anual da pessoa. Se ela possuir gastos com saúde, uma porcentagem desses gastos é abatida do imposto total.
 **Pessoa Jurídica:** O imposto cobrado é baseado em uma taxa padrão sobre o faturamento da empresa, mas essa taxa diminui caso a organização possua mais de 10 funcionários.

##  Estrutura de Pastas


java-tax-calculator/
└── src/
    └── Entidades/
        ├── Classe Contribuinte.java
        ├── classe PessoaFisica.java
        └── classe PessoaJuridica.java


---
Desenvolvido por [alexiacamille](https://github.com) ✨
