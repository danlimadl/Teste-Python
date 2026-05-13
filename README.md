# Teste-Python
Este programa extrai, processa e analisa o consumo de energia no Brasil, por subsistema (região) e por estação do ano.
O objetivo é fazer uma análise comparativa, através de gráficos, do consumo de carga validada nas regiões do Brasil entre janeiro de 2021 e dezembro de 2023. Os dados utilizados são extraídos da API do site Dados Abertos.

Funções:
1. Calcula a média de consumo por estação de cada subsistema. 
2. Identifica a estação e o ano com o consumo máximo e o mínimo de cada subsistema no período analisado.
3. Calcula a variação anual de consumo.
4. Cria gráficos comparativos

Para executar o programa é necessário:
1. Python 3.11
2. Gerenciador de pacotes "pip"

Clone o repositório do Github ou baixe o arquivo .ZIP no computador.

Instale as dependências que estão no arquivo requirements.txt e execute o programa consumo.py.

Após a execução, o programa cria um arquivo chamado Analise_Consumo.xlsx que contém tabelas com médias, máximos e mínimos e variação do consumo. E também cria um arquivo chamado log.txt com os logs das requisições à API e eventos do sistema 

autor: Daniel Pereira Lima.