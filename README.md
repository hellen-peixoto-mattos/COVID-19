# COVID-19 
### Pandemia coronavírus 2019
A COVID-19 é uma infecção respiratória aguda causada pelo coronavírus SARS-CoV-2. Trata-se de uma doença potencialmente grave, com alta transmissibilidade e alcance global.


Este projeto tem como objetivo desenvolver um dashboard interativo para exploração e visualização de dados sobre o avanço dos casos e da vacinação contra a COVID-19 no Brasil.

## Dados


Os dados sobre casos da **COVID-19** são compilados pelo centro de ciência de sistemas e engenharia da universidade americana **John Hopkins**. Esses dados  são atualizados diariamente desde janeiro de 2020 com uma granularidade temporal de dias e geográfica de regiões de países (estados, condados etc.). O website do projeto pode ser acessado neste [link](https://systems.jhu.edu/research/public-health/ncov/). Já os dados estão disponíveis no [link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports).

A seguir, estão descritos os dados derivados do seu processamento:

* **date:** data de referência;
* **state:** estado;
* **country:** país;
* **population:** população estimada;
* **confirmed:** número acumulado de infectados;
* **confirmed_1d:** número diário de infectados;
* **confirmed_moving_avg_7d:** média móvel de 7 dias do número diário de infectados;
* **confirmed_moving_avg_7d_rate_14d:** média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
* **deaths:** número acumulado de mortos;
* **deaths_1d:** número diário de mortos;
* **deaths_moving_avg_7d:** média móvel de 7 dias do número diário de mortos;
* **deaths_moving_avg_7d:** média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
* **month:** mês de referência;
* **year:** ano de referência.


O dashboard de dados contém os seguintes indicadores chaves de desempenho (key performance indicator ou KPI) consolidados:
1. Casos e mortes nas 24 horas;
2. Média móvel (7 dias) de casos e mortes;
3. Tendência de casos e mortes;
4. Proporção de vacinados com 1ª, 2ª e 3ª doses.

O dashboard de dados contém os seguintes gráficos para a análise exploratória de dados (exploratory data analysis ou EDA) interativa:
1. Distribuição do números de casos e mortes ao longo do tempo;
2. Distribuição da média móvel (7 dias) do números de casos e mortes ao longo do tempo;
3. Distribuição geográfica dos casos por estado por dia.

## Redes
* **Dashboard:**
  * Google Data Studio ([link](https://lookerstudio.google.com/reporting/0d8db6f1-66d6-4dd9-a875-1aa9182712d4)).

* **Processamento:**
  * Kaggle Notebook ([link](https://www.kaggle.com/code/hellenpeixoto/covid-19?scriptVersionId=191724264)).


## Visualização
* Casos por faixa:
![image](https://github.com/user-attachments/assets/c6fb3549-adb3-49db-aa32-e1e8af60cfcb)

* Mortes por faixa
![image](https://github.com/user-attachments/assets/d680c52e-d42a-4d66-9670-79ad96b2bd3a)

## Informações
* **Fontes:**
  * Casos pela universidade John Hopkins [link](https:////www.jhu.edu/));
  * Vacinação pela universidade de Oxford ([link](https://www.bbc.com/portuguese/geral-54698507)).
    
**Referências**

https://www.gov.br/saude/pt-br/coronavirus/o-que-e-o-coronavirus https://www.jhu.edu


