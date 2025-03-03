# Analise_Dados_Exp_Imp
Análise de dados de exportação e importação de produtos de classificação NCM 61 realizadas no período de 2019 a 2021 pelo Brasil.

## Sobre

- Para essa atividade extraí os dados do portal do Governo Federal disponíveis [aqui](https://dados.gov.br/dataset/estatisticos-do-comercio-exterior-brasileiro-de-bens/resource/d45d96ff-41e1-4c5e-bddd-5b633e1926a4?inner_span=True) e os importei para o Power BI onde pude fazer dois dashboards (um referente às exportações e outro às importações) e algumas análises.
- As planilhas de exportação e importação disponíveis no link são em formato .csv e contém todos os dados referentes ao período de 1997 a 2022, e a todas as classificações de produtos (NCM).
- Além disso foram importadas também as planilhas referentes ao código de país e via de transporte.
- As análises feitas a partir dos dashboards constam no documento "Analise_Exp_Imp_Brasil_NCM61.pdf" e os dashboards estão em formato .pdf.

## Tecnologia

  - Power BI
  
## Etapas
  
- [x] Carregamento das tabelas de exp. e imp. .csv completas no Power BI;
- [x] Importação de outras duas tabelas de correlação e classificação para os códigos das colunas "Código País" e "Código Via Transporte";
- [x] Relacionamento entre as três tabelas (Importação/exportação, classificação de países, código de via de transporte);
- [x] Filtragem da coluna ANO para 2019 a 2021;
- [x] Filtragem da coluna NCM para string iniciada em 61 (a análise era somente para NCM 61);
- [x] Desenvolvimento dos dashboards;
- [x] Análise e conclusões a partir dos dashboards.

<details>
  <summary><h2>Análise e Conclusões Finais</h2></summary>

# EXPORTAÇÕES

## Exportações por Ano:
- Ao todo foram 80.066 exportações no período analisado, somando um valor total de US$ 260.84 milhões.
- Em 2019 foram 26.673 exportações, em 2020 23.137 e em 2021 30.256 exportações.
- O número de exportações de 2021 é maior em relação ao de 2019, o que é um bom sinal. O ano de 2020 apresenta o menor número dentre os 3 anos. Provavelmente isso se dá em decorrência da pandemia.

## Exportações por País:
- O top 10 países para os quais o Brasil mais exporta não mudou desde 2019. Segue com as mesmas posições: Paraguai, Estados Unidos, Uruguai, Bolívia, Chile, Portugal, Japão, Costa Rica, Argentina e Equador, nessa ordem.
- Porém no ano de 2021 os Estados Unidos vêm alcançando o Paraguai e praticamente empatando no número de exportações (Paraguai com 3.495 e Estados Unidos com 3.477). Dessa forma espera-se que os Estados Unidos alcancem a primeira posição no ano de 2022.
- Além disso o top 3, 4 e 5 ocupados por Uruguai, Bolívia e Chile, respectivamente, apresentavam uma diferença no número de exportações bem delimitada. No ano de 2021 a diferença se torna mínima. Bolívia e Chile exibem números parecidos.

## Exportações por Mês:
- Dezembro é o mês com o maior número de exportações, seguido por junho, considerando todo o período analisado.
- Janeiro é o mês com o menor número de exportações, seguido por fevereiro.
- Do mês de março a abril o número de exportações passa a alcançar a média anual.

## Vias de Transporte:
- A via de transporte mais utilizada é a via aérea seguida por rodoviária e marítima.
- A via aérea é majoritariamente o transporte padrão para os Estados Unidos, Chile, Portugal, Japão, Costa Rica e Equador.
- Para o Paraguai, Uruguai e Argentina as exportações são em sua maioria por via rodoviária.
- Para a Bolívia fica dividido entre via aérea e rodoviária, porém a última é mais frequente.
- A via marítima, terceiro maior meio utilizado é mais frequente em exportações para a Costa Rica.

# IMPORTAÇÕES

## Importações por Ano:
- Ao todo foram 68.960 importações no período analisado, somando um valor total de US$ 2.09 bilhões.
- Em 2019 foram 26.917 importações, em 2020 19.679 e em 2021 22.364 importações.
- O número de importações no ano de 2021 é menor que no ano de 2019, uma queda significativa. Em 2020 também houve uma baixa, como no caso das exportações, porém até o ano seguinte houve uma pequena crescente.

## Importações por País:
- O top 10 países dos quais o Brasil mais importa também não mudou desde o ano de 2019. É liderado pela China com uma grande diferença da Itália, e Vietnã, segundo e terceiro países respectivamente.
- A tendência é que permaneça na mesma ordem, pois os países apresentam uma crescente parelha entre os anos.

## Importações por Mês:
- Fevereiro é o mês com maior número de importações, seguido por março.
- Abril é o mês com o menor número de importações, seguido por junho.
- Abril, maio, junho, julho, outubro, novembro e dezembro ficam abaixo da média anual de importações, considerando todo o período.

## Vias de Transporte:
- A via de transporte mais utilizada nas importações é a via marítima, seguida por aérea e por entradas/saídas fictas.
- A via marítima é a mais frequente em importações da China, Vietnã, Bangladesh, Camboja e Sri Lanka. Os outros países utilizam mais as vias aéreas.
</details>
