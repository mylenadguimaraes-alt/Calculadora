# Calculadora

Projeto de uma calculadora web desenvolvida com HTML, CSS e JavaScript. A aplicação permite realizar operações matemáticas básicas de forma simples e rápida.

## Sobre o projeto

A calculadora foi desenvolvida como um projeto para praticar conceitos de desenvolvimento web, principalmente a integração entre HTML, CSS e JavaScript.

O usuário informa dois números e pode escolher entre quatro operações:

* Soma
* Subtração
* Multiplicação
* Divisão

O resultado é apresentado diretamente na página.

## Funcionalidades

* Inserção de dois números.
* Realização de soma.
* Realização de subtração.
* Realização de multiplicação.
* Realização de divisão.
* Validação dos campos antes da operação.
* Verificação de divisão por zero.
* Exibição do resultado na própria página.
* Botão para limpar os campos e o resultado.
* Layout responsivo para diferentes tamanhos de tela.

## Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript

## Estrutura do projeto

```text
Calculadora-master/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── img/
    └── logo.png
```

### index.html

Responsável pela estrutura da página e pelos elementos da calculadora, como campos de entrada, botões das operações e área de resultado.

### css/style.css

Responsável pela estilização da aplicação, incluindo:

* Cores
* Espaçamentos
* Bordas
* Botões
* Formulário
* Área de resultado
* Responsividade

### js/script.js

Contém as funções responsáveis pelo funcionamento da calculadora:

* `fSoma()` — realiza a soma dos dois números.
* `fSubtracao()` — realiza a subtração.
* `fMultiplicacao()` — realiza a multiplicação.
* `fDivisao()` — realiza a divisão e verifica se o segundo número é zero.
* `fLimpar()` — limpa os campos e redefine o resultado.

### img/logo.png

Imagem utilizada como ícone da página.

## Validações

Antes de realizar uma operação, o sistema verifica se os dois campos foram preenchidos com valores numéricos.

Na operação de divisão, também existe uma validação para impedir a divisão por zero.

## Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.
4. Informe os dois números.
5. Escolha a operação desejada.

Não é necessário instalar nenhuma dependência ou configurar um servidor para executar o projeto.

## Objetivo

O objetivo do projeto é desenvolver uma aplicação simples utilizando conceitos fundamentais de desenvolvimento web, praticando estruturação com HTML, estilização com CSS e lógica de programação com JavaScript.

## Autor

Mylena Dantas Guimarães
