# Desafio-1-DIO--Registro-de-Transacoes-Bancarias
# Desafio - Registro de Transações Bancárias

## Descrição

Você está desenvolvendo um programa simples em Java para manter um registro de transações bancárias. Cada transação é armazenada em uma lista.

## Entrada

O programa solicitará ao usuário que informe o saldo inicial da conta. Em seguida, o programa solicitará a quantidade total de transações que o cliente deseja realizar.

### Entrada de Transações:

Para cada transação, o programa solicitará ao usuário:
- O tipo de transação: Digite 'D' para depósito ou 'S' para saque.
- O valor da transação.

## Saída

Utilizando listas (ArrayList ou LinkedList), o programa armazenará cada transação, que incluirá um tipo (Depósito ou Saque) e um valor. Ao final das transações, o programa exibirá o saldo final da conta e a lista de transações.

## Exemplos

### Exemplo 1

#### Entrada

| Valor | Descrição                        |
|-------|----------------------------------|
| 2500  | Saldo inicial                    |
| 2     | Quantidade total de transações   |
| d     | Tipo de transação: Depósito      |
| 100   | Valor da transação               |
| s     | Tipo de transação: Saque         |
| 500   | Valor da transação               |

#### Saída

| Valor            | Descrição                            |
|------------------|--------------------------------------|
| Saldo: 2100.0    | Saldo final                          |
| Transações:      |                                      |
| 1. Depósito de 100.0 |                                      |
| 2. Saque de 500.0    |                                      |

### Exemplo 2

#### Entrada

| Valor | Descrição                        |
|-------|----------------------------------|
| 900   | Saldo inicial                    |
| 1     | Quantidade total de transações   |
| s     | Tipo de transação: Saque         |
| 100   | Valor da transação               |

#### Saída

| Valor            | Descrição                            |
|------------------|--------------------------------------|
| Saldo: 800.0     | Saldo final                          |
| Transações:      |                                      |
| 1. Saque de 100.0 |                                      |

### Exemplo 3

#### Entrada

| Valor | Descrição                        |
|-------|----------------------------------|
| 0     | Saldo inicial                    |
| 0     | Quantidade total de transações   |

#### Saída

| Valor         | Descrição      |
|---------------|----------------|
| Saldo: 0.0    | Saldo final    |
| Transações:   |                |
| Nenhuma       |                |

## Instruções

1. Copie o código Java fornecido e cole em um arquivo chamado `Main.java`.
2. Compile o arquivo com o comando `javac Main.java`.
3. Execute o programa com o comando `java Main`.
4. Siga as instruções do programa para informar o saldo inicial, a quantidade de transações, e os detalhes de cada transação.
5. Visualize o saldo atualizado e a lista de transações ao final da execução.
