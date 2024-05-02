# ADO: API de Cálculo de Equação do Segundo Grau com Autenticação

## Descrição
Este é um projeto de API em Node.js que permite aos usuários autenticados calcular equações do segundo grau. A API fornece endpoints para registro de usuários, login e cálculo da equação do segundo grau. A autenticação de usuários é feita manualmente e os dados dos usuários são armazenados em memória.

## Requisitos
- Implementação da autenticação de usuário com login e senha.
- Os usuários podem se registrar na API.
- Apenas usuários autenticados podem acessar o serviço de cálculo da equação do segundo grau.
- O serviço de cálculo aceita os coeficientes (a, b, c) da equação do segundo grau e retorna as raízes, se existirem, ou uma mensagem indicando que não existem raízes reais.
- Os dados dos usuários são armazenados em memória durante a execução da aplicação.

## Informações
A equação do 2º grau é uma equação que possui o formato ax^2 + bx + c = 0, com a, b, c ∈ ℝ e a ≠ 0. Quando uma equação do segundo grau se encontra em seu formato completo, é possível resolvê-la utilizando a famosa fórmula de Bhaskara ou então, o método da soma e produto.
