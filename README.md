# **Tutorial de Utilização da Biblioteca Mplfinance**

Este tutorial foi inspirado em uma aula do professor Leandro Guerra cujo link encontra-se no item fontes de pesquisa. Desde já agradeço ao professor por todo conteúdo disponibilizado.

### **Objetivo:**
O objetivo deste tutorial é auxiliar estudantes da análise de dados financeiros à construir gráficos de *candlestick* de forma simples com a biblioteca mplfinance.

## **Composição:**
O projeto é composto de três arquivos, além deste README:
* O primeiro contém uma função que coleta os dados financeiros de uma empresa preestabelecida, realiza o tratamento e a inclusão de um indicador chamado bandas de bollinger e de marcadores e realizar a persistência em disco destas tarefas;
* O Segundo é o arquivo criado e persistido em dico em formato joblib;
* Por fim, o terceiro arquivo contém o tutorial de utilização da biblioteca mplfinance.

## **Sumário:**
1. Criação de gráfico simples, por padrão o gráfico é gerado no padrão de gráfico de barras;
2. Criação de gráfico de linhas: ```type="line"```;
3. Criação de gráfico com volume: ```volume=True```;
4. Criação de gráfico de candlesticks: ```type="candle"```;
5. Criação de gráfico com a utilização de médias móveis: ```mav=N```;
6. Criação de gráfico com delimitação de período: ```data["YYYY"]```;
7. Outras configurações: ```figratio```,  ```title```, ```tight_layout```, ```style```, ```show_nontrading```, ```ylabel```;
8. Realizando configurações específicas com a função ```mpf.make_mpf_style()```;
9. Incluindo gráficos com a função ```mpf.addplot```;
    
Fontes de Pesquisa:
* [Aula 4 - Candlesticks e sinais no Python - Python para Finanças Quantitativas](https://www.youtube.com/watch?v=PiS7WYe6q-w&t=1171s)
* [How to plot a candlestick chart in python. It's very easy!](https://www.youtube.com/watch?v=GcXgxfbcFrQ)

Vale á pena salientar que este estudo representa um tutorial básico. Para um estudo mais detalhado estudar a documentação da biblioteca.
