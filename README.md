# covid-status
Primeiro Desafio -  2022-1A - MBA - Bootcamp Desenvolvedor(a) REACT

Objetivos
Exercitar os seguintes conceitos trabalhados no Módulo:
✓ Implementação de aplicação com JavaScript puro.
✓ Utilização de bibliotecas (Chart.js, Axios...).
Enunciado
Construção de um Dashboard com elementos gráficos apresentando os números da Covid-19 a ser
consumido de uma API, utilizando JavaScript puro e HTML.

Atividades
Os alunos deverão desempenhar as seguintes atividades:
1. Implementar um JavaScript puro, HTML e CSS, uma aplicação para apresentação dos
números da COVID-19 de um determinado país para um período de datas. A URL base para
consumo da API com os dados da COVID é https://api.covid19api.com/. As respectivas rotas
serão descritas nas atividades subsequentes.
2. A imagem abaixo ilustra um exemplo de implementação dessa aplicação, com um tipo de
estilização obtido da internet (https://keen.io/). O estilo da página não necessariamente
precisa ter o mesmo layout apresentado, mas é importante ter os mesmos componentes. O
projeto base (HTML e CSS) será disponibilizado no fórum de avisos do professor, caso
queiram utilizá-lo como referência.
A página apresentada na Figura 1 trata-se da Home de sua aplicação. Nela devem ser apresentados
os números globais, até a data corrente, retornados pela API na rota “/summary”, sendo eles:
KPIs: Total de Confirmados, Total de Mortes e Total Recuperados.
Pizza: Novos Confirmados, Novas Mortes e Novos Recuperados
Barras: Pareto com o Top 10 no número de mortes por país.
Figura 1 – Home page da aplicação.
A página apresentada na Figura 2 trata-se das informações diárias por País, acessada pelo menu
superior País. Os elementos apresentados na página são:
Filtros: Data Início, Data Fim, País (combo retornado pela rota “/coutries”), Dados (Casos
Confirmados, Número de Mortes e Casos Recuperados) e o um botão para aplicar os filtros
selecionados.
Gráfico de Linhas: Apresentação diária dos números do tipo de dados selecionados pelo filtro
(Confirmados, Mortes ou Recuperados). Apresentar no gráfico a linha com o número médio
correspondente aos números apresentados na curva diária.
KPIs: Total de Confirmados, Total de Mortes e Total de Recuperados para o país selecionado.
Figura 2 – Apresentação dos números diários de um país.
3. Nas informações por país, foi utilizada a rota “By Country All Status”. Mais detalhes e
exemplos podem ser avaliados na documentação da API:
https://documenter.getpostman.com/view/10808728/SzS8rjbc
