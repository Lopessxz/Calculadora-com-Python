<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora em Python - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Calculadora em Python</h1>
        <p>Este projeto consiste em uma calculadora simples que opera via linha de comando. O usuário pode escolher entre diferentes operações matemáticas e inserir números para realizar cálculos.</p>
        <h2>Requisitos Técnicos</h2>
        <ul>
            <li>Laços de repetição</li>
            <li>Condicionais</li>
            <li>Entrada e saída de dados</li>
            <li>Operações matemáticas</li>
            <li>Coleções de dados</li>
        </ul> 
        <h2>Descrição Geral</h2>
        <p>Desenvolver um aplicativo de calculadora que funcione via linha de comando (terminal). O usuário deve ser capaz de escolher entre diferentes operações matemáticas, inserir números para realizar os cálculos, e navegar no menu do aplicativo.</p>
        <h2>Requisitos Funcionais</h2>
        <h3>Menu Principal</h3>
        <p>Ao iniciar, o aplicativo deve exibir um menu principal com as seguintes opções:</p>
        <ul>
            <li>1 - Soma</li>
            <li>2 - Subtração</li>
            <li>3 - Multiplicação</li>
            <li>4 - Divisão</li>
            <li>s - Sair</li>
        </ul>
        <p>O usuário escolhe uma operação digitando o número correspondente. Se o usuário digitar "s", o aplicativo deve exibir uma mensagem de agradecimento e encerrar.</p>
        <h3>Execução da Operação</h3>
        <p>Após escolher uma operação, o usuário deve ser solicitado a inserir dois números, um por vez, pressionando "Enter" após cada um. O aplicativo calcula e exibe o resultado da operação escolhida com os números fornecidos.</p>
        <p><strong>Dica:</strong> tome cuidado com divisões por zero!</p>
        <p>Após exibir o resultado, o aplicativo retorna automaticamente ao menu principal.</p>
        <h2>Instruções de Uso</h2>
        <pre>
python calculadora.py
        </pre>
        <p>O comando acima inicia o aplicativo. Siga as instruções na tela para navegar pelo menu e realizar cálculos.</p>
    </div>
</body>
</html>
