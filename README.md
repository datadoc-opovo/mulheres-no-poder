
## Ceará ocupa a 24 posição nacional, em representatividade de gênero na política

Este repositório é uma forma garantir o compromisso com a transparência, integridade e confiabilidade das análises e materiais da Central de Jornalismo de Dados do O POVO (DATADOC). Disponibilizamos aqui as bases de dados (originais e analisadas) e códigos para replicação, referente a análise da igualdade de gênero na política no Estado do Ceará e no Brasil.


![grafico](https://user-images.githubusercontent.com/86378838/163450465-e8ec0231-33bb-4dc3-ab76-949e61cc9b46.png)


----------------------
### Fonte e coleta de dados:

A Central DATADOC, por meio da *API* [ Brasilian Elections Python](https://github.com/Cepesp-Fgv/cepesp-python), desenvolvida pelo [CEPESPdata](https://cepespdata.io/), coletou os dados de todas as candidaturas no Brasil, em eleições gerais nacionais, entre 1998 e 2018. A base contém, dentre outros campos, o gênero, raça, escolaridade e cargo das candidaturas e pessoas eleitas em cada eleição.

### Material disponibilizado:
  
Os códigos para coleta e processamento dos dados estão disponíveis [neste notebook](/InfoViz_Mulheres_no_Poder.ipynb), em python. Outras visualizações e análises estão disponíveis [nesta página](https://observablehq.com/embed/@cajazeiraramos/infoviz-mulheres-no-poder?cells=scrollChart%2Cgeral%2CdownloadG%2Ctitle%2Cviewof+apenas_eleitos%2Cviewof+selected_uf%2Cviewof+selected_partido%2CdownloadG1%2Cfonte%2Ctitle2%2CdownloadG2%2CscrollChart2%2Cfonte2%2Ctitle3%2CdownloadG3%2Cviewof+year2%2Cviewof+cb_cargos%2CdatavizMap%2Clegenda_mapa%2Cfonte3). A base de dados utilizada na reportagem, bem como os recortes e valores agregados em cada gráfico, estão listados abaixo:

#### Arquivos gerados:

 - Base de dados completa [neste arquivo](/arquivos_gerados/dados_eleicoes.csv);
 - [Proporção entre homens e mulheres eleitas no Ceará, por Cargo e Eleição](/arquivos_gerados/Proporção entre homens e mulheres eleitas no Ceará, por Cargo e Eleição.csv);
     - Gráfico disponível [neste link](https://public.flourish.studio/visualisation/9289780/)
 - [Percentual de mulheres eleitas no Brasil por UF, Cargo e Eleição]()
     - Gráfico disponível [neste link](https://observablehq.com/embed/@cajazeiraramos/infoviz-mulheres-no-poder?cells=datavizMap%2Cviewof+year2%2Cviewof+cb_cargos%2Clegenda_mapa%2Cfonte3)
 - [Proporção entre homens e mulheres eleitas no Brasil, por Cargo e Eleição]()
     - Gráfico disponível [neste link](https://public.flourish.studio/visualisation/9044760/)
 - [Percentual de mulheres entre candidatos e eleitos no Ceará, por eleição]()
     - Gráfico disponível [neste link](https://public.flourish.studio/visualisation/9298839/)
 - [Distribuição da Raça/Cor das mulheres candidatas e eleitas no Brasil em 2018]() 
     - Gráfico disponível [neste link](https://public.flourish.studio/visualisation/9287731/)
 - [Escolaridade das Mulheres eleitas no Ceará]()
     - Gráfico disponível [neste link](https://public.flourish.studio/visualisation/9290164/)

#### Como utilizar:

Para executar o notebook com a coleta e processamento dos dados, é necessário um ambiente com *Python3* e duas dependências que podem ser facilmente instaladas via [Pip](https://pypi.org/project/pip/): 
```{python}
!pip install pandas
!pip install electionsBR
```


### A central DATADOC

A Central de Jornalismo de Dados do O POVO (DATADOC) alia tecnologia e técnicas diversas de análises de dados para produzir um jornalismo de precisão. Para que você forme sua opinião com segurança. Nosso objetivo é fazer com que todos tenham acesso aos dados utilizados nas notícias que produzimos.

A DATADOC é composta por uma equipe de três jornalistas (sendo uma infografista), uma desenvolvedora front-end e um cientista da computação, que coletam, enriquecem e disponibilizam as bases e códigos de cada reportagem para um jornalismo transparente e baseado em evidências.

 ---------------------------------------
#### 🔥📰👩🏻‍💻 Se você gostou do nosso material, apoie assinando o OP+ e acompanhando o nosso trabalho.

#### 📝📨 Para feedback, dúvidas ou sugestões: datadoc@opovodigital.com

--------------------------------------
 
🗓️🕵🏻 Confira também outras produções recentes da central DATADOC: O especial ***#CredosDeFortaleza***, que revelou benefícios fiscais indevidos, templos fantasmas e os principais devedores do fisco, está disponível no link: [https://bit.ly/3gkGPyF](https://bit.ly/3gkGPyF)
