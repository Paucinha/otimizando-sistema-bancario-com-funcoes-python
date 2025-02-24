# Desafio: Otimizando o Sistema Bancário com Funções Python

![GitHub](https://img.shields.io/github/license/Paucinha/api-ecommerce-dio?style=flat-square)

Neste desafio, você terá a oportunidade de otimizar o Sistema Bancário previamente desenvolvido com o uso de funções Python. O objetivo é aprimorar a estrutura e a eficiência do sistema, implementando as operações de depósito, saque e extrato em funções específicas. Você terá a chance de refatorar o código existente, dividindo-o em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo. Prepare-se para aplicar conceitos avançados de programação e demonstrar sua habilidade em criar soluções mais elegantes e eficientes utilizando Python.

**Python**

**Back-End | Avançado**

## Objetivo

Separar as funções existentes de saque, depósito e extrato em funções; Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

## Desafio

Precisamos deixar nosso código maís modularizado, para isso vamos criar fuções para s operações existentes: sacar, depositar e visualizar histórico. Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usu´rio).

## Separação em funções

Devemos criar funções para todas as operações do sistema. Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. O retorno é a forma como serão chamadas, pode ser definida por você dá forma que achar melhor.

## Saque

A função saque deve receber os argumentos apenas por nome (Keywords only).  Sugestão de argumentos: saldo, valor, extrato, limite, `numero_saques`, `limite_ saques`. Sugestão de retorno: saldo e extrato.

## Depósito

A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.

## Extrato

A função extrato deve receber os argumentos por posição e nome (positional only e keywords only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

## Novas funções

Precisamos criar duas novas funções: criar usuário e criar conta corrente. Fique a vontade para adicionar mais funções, exemplo: listar contas.

## Criar usuário (cliente)

O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, CPF e endereço. O endereço é uma string com o formato: Logradouro, nro - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não podemos cadastrar 2 usuários com o mesmo CPF.

## Criar conta corrente 

Programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: “0001”. O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.
 
:exclamation: **Dica:** Vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF, informando para cada usuário da lista.

![text](https://assets.dio.me/IwGGaOEYVw9pPUMVGEaqp7eKn1gV22wDOHmmAmI0zDY/f:webp/h:221/q:80/L3RyYWNrcy9jb3Zlci83OWZiNzhkZC0xNTQ3LTQ0N2YtYTNkOC04ZGQwMWU1YWMzNTEucG5n)

##

Projeto desenvolvido durante o [**Bootcamp Suzano - Python Developer**](https://www.dio.me/bootcamp/suzano-python-developer), fornecido pela [**DIO**](https://www.dio.me/)

##

- [By Páucinha](https://github.com/Paucinha)
