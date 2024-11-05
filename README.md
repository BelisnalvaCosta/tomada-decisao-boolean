# tomada-decisao-boolean

Projeto feito na IDE Visual Studio Code, linguagem: HTML, JacvaScript e CSS [^1].

Este projeto tem como objetivo praticar e memorizar a tabela verdade. Fiz com HTML para melhor fixação da matéria da Univesp/SP.

Desafio: Obtenha uma árvore de decisão para representar a operação de uma porta lógica. Sendo que A, B são variáveis booleanas, 
que representam as entradas e Y representa a saída da porta lógica, para as duas situações abaixo representadas pelas seguintes tabelas-verdade:

## Explicação

1. Seletor de visualização:  
   A `<select id="viewType">` adiciona a escolha entre `lamp` (lâmpada) e `car` (carro) para a representação visual.

2. Função `createOutput(value)`:  
   - A função `createOutput` agora usa o valor do `viewType` para selecionar a imagem correta.
   - Se `viewType` é "lamp", a função usa `lamp_on.jpg` para o valor `1` e `lamp_off.jpg` para o valor `0`.
   - Se `viewType` é "car", ela usa `carro_on.jpg` para `1` e `carro_off.jpg` para `0`.

3. Imagens:  
   - Imagens `lamp_on.jpg`, `lamp_off.jpg`, `carro_on.jpg`, e `carro_off.jpg`.

# Tecnologia  utilizada

## Front-end

## LINGUAGEM:

![HTML](https://img.shields.io/badge/HTML-000?style=for-the-badge&logo=html5&logoColor=30A3DC)
![CSS](https://img.shields.io/badge/CSS-000?style=for-the-badge&logo=css3&logoColor=E94D5F)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=30A3DC)

  <table>
  <tr>
    <td>
      <img width="80px" align="center" src="https://avatars.githubusercontent.com/BelisnalvaCosta"/>
    </td>
    <td align="left">
      <a href="https://github.com/BelisnalvaCosta">
        <span><b>Belisnalva Costa</b></span>
      </a>
      <br>
      <span>Aprendendo a desenvolver Front-end na prática!</span>
    </td>
  </tr>
</table>

## Referências
Professor: Prof. Dr. Alexandre da Silva Simõe - Semana 5

- [Aplicações em Aprendizado de Máquina](https://ava.univesp.br/ultra/courses/_13240_1/cl/outline)

[^1]: Este projeto é um protótipo que elaborei com apoio da Openai ChatGPT, 4.0 (IA generativa) para corrigir bugs e aperfeiçoamento do Desafio.
