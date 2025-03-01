﻿# Calculadora - Testes Unitários

Este projeto contém testes unitários para uma calculadora simples, desenvolvida em JavaScript, com o objetivo de validar as operações matemáticas básicas: soma, subtração, divisão e multiplicação.

## Funcionalidades

- **Soma**: Realiza a adição de dois números.
- **Subtração**: Realiza a subtração entre dois números.
- **Divisão**: Realiza a divisão entre dois números.
- **Multiplicação**: Realiza a multiplicação entre dois números.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript.
- **Jest**: Framework de testes para JavaScript.

## Testes

Os testes são feitos para verificar se os resultados das operações estão corretos. Alguns dos testes realizados:

- Verifica se a soma de dois números retorna o valor esperado.
- Verifica se a subtração retorna o valor correto.
- Verifica se a divisão retorna o resultado correto.
- Verifica se a multiplicação está funcionando corretamente.

## Como Executar os Testes

1. Clone o repositório:
    ```bash
    git clone https://github.com/usuario/calculadora-teste.git
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute os testes:
    ```bash
    npm test
    ```

## Exemplo de Teste

```javascript
test('Testando soma', () => {
    const esperado = 25;
    const retorno = soma(15, 10);
    expect(retorno).toBe(esperado);
});
