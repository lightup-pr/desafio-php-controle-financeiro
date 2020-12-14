Desafio PHP | Controle Financeiro
==========================

Nós esperamos ver como você testa seu código, se você segue boas práticas de programação e como resolve problemas.

Você deverá enviar seu código para o GitHub (ou algum outro serviço git). Os desafios 2 e 3 devem ser publicados em algum servidor web para testes.

---

# 1. Validar Caracteres

Escreva uma função que receba uma string contendo alguns caracteres e determine se a ordem é válida. Os caracteres considerados são representados da seguinte forma: (, ), {, }, [ ou ].

Para ser considerado válido a entrada da função deve seguir as seguintes condições:

* Não deve conter caracteres incompatíveis;
* Um caractere de abertura deve possuir seu respectivo caractere de fechamento;
* Um subconjunto de caracteres deve ser uma sequencia válida de caracteres;


## Exemplos:

**Entradas Válidas:**

* ()
* (){}[]
* [{()}](){}
* [{()}][(){}]

**Entradas Inválidas:**

* (
* []{()
* [{)]
* [{()}}](){}

---

# 2. Backend - Controle Financeiro

Você criará uma api para controle de saldo de pessoas identificadas pelo CPF. 

#### Funcionalidades

* Saldo: Deverá retornar o saldo de uma pessoa.

* Extrato: Deverá retornar as operações realizadas por uma pessoa.

* Débito: Essa operação deverá retirar do saldo de uma pessoa o valor informado na requisição.

* Crédito: Essa operação deverá adicionar ao saldo da pessoa o valor informado na requisição.

* Transferências: Essa operação deverá realizar o débito do saldo de uma pessoa e realizar um crédito na outra pessoa.

#### Observações

* Não é permitido saldo negativo.

* Todas as operações devem ser registradas.

* Não se preocupe em validar o CPF.

* Utilizar git para controle de versão, fazendo vários commits explicando o que foi feito.

* Você poderá utilizar qualquer framework PHP.

* Usar um banco de dados relacional

#### Objetivos

Queremos saber como você utiliza orientação a objetos para resolver problemas e como você trabalha com banco de dados relacional.

---

# 3. Frontend - Controle Financeiro

Crie uma aplicação web simples para consumir as apis criadas no segundo desafio. 

Você pode ficar livre para definir o layout e as tecnologias usadas nessa aplicação.

---

## Boa sorte!
