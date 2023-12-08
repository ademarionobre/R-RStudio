# Limpeza e Preparação de dado com o R

## Objetivo
O objetivo deste repositório é abordar o conhecimento básico em R aos pacotes da biblioteca **Tidyverse**. A partir de problemas reais de análise de dados, verems técnicas de coleta, limpeza e organização de dados. Para isso,
será introduzido o operador pipe: ````|>```` ou ````%>%```` e utilizaremos principalmente os pacotes: **dplyr** e **tidyr**  

## Tópicos

**1: Introdução e motivação ao uso Tidyverse, introdução ao operador Pipe**

Utilização ao tidyverse, mostrando os pacotes: dplyr, tidyr, readxl, readr e purr, e também pacotes mais avançados que não serão abordados no curso, mas que são do tidyverse e utilizam do jeito ‘tidy’ de se programar,
como: tidymodels(modelagem), tsibble e fable(dados e modelos de série temporal).  
Além disso, o operador pipe será introduzido, operador esse fundamental para se utilizar o tidyverse

• Introdução ao tidyverse  
• Motivação: tidymodels(modelagem), tsibble e fable(dados e modelos de série temporal)  
• Operador Pipe, para que serve e como utilizar

**2: Carregando Conjunto e Limpeza Inicial de dados e um tibble**

Pacote de carregamentos de dados readr e readxl serão introduzidos, o pacote janitor será utilizado para uma limpeza inicial dos dados, e o data.frame do tidyverse, chamado de tibble será introduzido, onde abordaremos as
principais diferenças entre um data.frame, um tibble e data.table

• Introdução ao conjunto de dados utilizado  
• Introdução ao readr e readxl  
• Limpeza Inicial com o pacote Janitor  
• Entendendo o que é um tibble  

**3: Limpeza e Organização dos Dados**
Introducão dos pacotes dplyr e tidyr. As funções principais de cada pacote serão exemplificadas, mostrando o fluxo de limpeza e organização padrão tidy.

• Introdução as funções: mutate, select, filter do pacote Dplyr  
• Introdução as funções: pivot_longer e pivot_wider do pacote Tidyr

**4: Agrupamento e Joins**

Objetivo demonstrar as formas de agrupamento de dados realizados via Dplyr, além disso a funções de junção de 2 conjunto de dados, abordando joins.

• Introdução as funções: group_by, summarise, reframe do pacote Dplyr, utilzados na parte de agrupamento de dados  
• Introdução as funções: joins do pacote Dplyr, utilizadas em operações entre pares de data.frame


**5: Teste prático**  
Objetivo gerar e entregar resultados de um teste com um conjunto de dados ‘cru’, uma limpeza e organização.

______
## Refêrencias:
• Boehmke, Bradley C. (2016) Data Wrangling with R (http://link.springer.com/book/10.1007%2F978-3-319-45599-0)  
• Grolemund, G & Wickham, H (2023): R for Data Science (https://r4ds.hadley.nz)  
• Wickham, H. (2014): Tidy Data https://www.jstatsoft.org/article/view/v059i10
