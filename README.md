# IT304 - Tópicos em Sistemas de Energia Elétrica I <br/> Comercialização de Energia Elétrica para Grandes Clientes

# Pré-análise das Faturas - UFRJ/Centro de Tecnologia

# Descrição Resumida do Projeto

Este trabalho apresenta uma pré-análise das faturas de energia elétrica do Centro de Tecnologia (CT) da Universidade Federal do Rio de Janeiro para os anos de 2017, 2018 e 2019. Primeriamente, é apresentada uma breve descrição do CT, apresentando sua localização, o número de alunos que frequentam esta unidade, qual a concessionária de energia elétrica que atende esta UC, qual o grupo de consumidores no qual esta UC está inserida, além de alguns outros aspectos que possam auxiliar no entendimento da UC estudada.

Em seguida, são realizadas análises acerca da qualidade dos dados disponíveis, como por exemplo se há ou não a ausência de faturas, análises sobre o perfil de consumo da UC considerando os períodos de ponta e fora da ponta, além de uma análise dos custos devido a este perfil de consumo. São realizadas também análises da demanda contratada, buscando identificar se esta está adequada para a UC em questão. Por fim, são realizadas análises sobre o fator de potência da UC, buscando identificar se há excesso de reativos e se há a necessidade de realizar a correção do fator de potência.

# Abstract in English
~~~
<English version of the abstract.>
~~~

# Equipe
 Douglas Machado Côrtes - RA: 233270 <br/>
 Hever Alcahuaman Villanueva - RA: 228105 <br/>
 Luís Henrique Bandória - RA: 155449 <br/>
 Roberto Tilhaqui Junior - RA: 233671 <br/>

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação
~~~
<Descrição do tema do projeto, incluindo motivação, contexto gerador e caracterização do problema. A introdução também pode apresentar iniciativas correlatas para lidar com o problema (não obrigatório) e deve introduzir de forma mais detalhada que o resumo a solução proposta e resultados alcançados. Aqui também são apresentadas as seções do projeto.>
~~~

## Perguntas de Pesquisa

Este estudo tem como objetivo realizar diferentes análises preliminares para determinar a possibilidade de migração de um contrato de energia elétrica do Ambiente de Contratação Regulada para o Ambiente de Contratação Livre (ACR/ACL) como medida econômica. Esta análise está limitada ao Centro de Tecnologia da UFRJ, unidade consumidora escolhida para análise.

## Objetivos do Projeto

Os objetivos deste estudo se resumem em verificar se há a possibilidade de migração de um contrato de energia elétrica do Ambiente de Contratação Regulada para o Ambiente de Contratação Livre (ACR/ACL) para a unidade consumidora escolhida. Para tal, serão realizadas análises acerca da qualidade dos dados disponíveis, como por exemplo se há ou não a ausência de faturas. Em seguida, serão realizadas análises buscando identificar o perfil de consumo da unidade consumidora em questão considerando o consumo nos períodos de ponta e fora da ponta, além de uma análise dos custos decorrentes deste perfil de consumo. Serão realizadas também análises sobre a demanda contratada, buscando identificar se esta está adequada para a unidade consumidora em questão ou se há a necessidade de uma revisão da demanda contrada. Por fim, serão realizadas análises sobre o fator de potência da unidade consumidora, buscando identificar se o fator de potência esta dentro dos limites estabelcidos pelas normas ou se há a necessidade da realização da correção do fator de potência da instalação. Todas as análises serão realizadas para os anos de 2017, 2018 e 2019.

# Recursos e Métodos

## Bases de Dados

A Tabela 1 apresenta uma descrição dos dados utilizados no projeto referente as faturas de energia dos anos de 2017, 2018 e 2019, bem como traz um link para encontrar os dados disponíveis no aplicativo Google Drive. Além dos links, os dados estão disponíveis na pasta /data no formato .xlsx.

Tabela 1: Dados das Faturas de Energia Elétrica
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ano de 2017 | https://drive.google.com/file/d/1nAatA3B2JmC2uIUY10GiAe9smT-1Q2Cc/view?usp=sharing | Faturas Digitalizadas para o ano de 2017.
Ano de 2018 | https://drive.google.com/file/d/1VvRmQD-MoJczpMMejnxBmGbnM0nYHPMo/view?usp=sharing | Faturas Digitalizadas para o ano de 2018.
Ano de 2019 | https://drive.google.com/file/d/17Gyi0AzNh-rDwgOLgIPcGGlBRSPz0wwe/view?usp=sharing | Faturas Digitalizadas para o ano de 2019.

## Ferramentas

A Tabela 2 apresenta uma descrição das ferramentas computacionais utilizadas no projeto juntamente a uma breve descrição de cada uma.

Tabela 2: Ferramentas Computacionais utilizadas
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Google Sheets | https://www.google.com/sheets/about/ | Ferramenta para construção de planilhas de dados online. Usada para digitalizar as faturas de energia.
LibreOffice Calc | https://pt-br.libreoffice.org/descubra/calc/ | Ferramenta para construção de planilhas de dados de código aberto. Usada para digitalizar as faturas de energia.
Jupyter Notebook | https://jupyter.org/ | Editor Python no formato Notebook. Usada para gerar as curvas/gráficos apresentados no trabalho.

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~

## Detalhamento do Projeto

O código em Python/JupyterNotebook desenvolvido para produzir as figuras apresentadas nos Resultados e Discussão pode ser acessado através do link abaixo. Este script pode ser executado online, sem necessidade de instalção ou download dos dados. 

Script Desenvolvido | https://mybinder.org/v2/gh/156449/IT304---Grupo-5.git/HEAD

# Resultados e Discussão

## Análise do Consumo de Energia

### Consumo de Energia

A Figura 1a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2017. A Figura 1b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2017 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Consumo2017.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ProporçãoConsumo2017.svg?raw=true) |
|:--:|:--:|
| Figura 1a: Consumo Ponta e Fora da Ponta | Figura 1b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 2a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2018. A Figura 2b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2018 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Consumo2018.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ProporçãoConsumo2018.svg?raw=true) |
|:--:|:--:|
| Figura 2a: Consumo Ponta e Fora da Ponta | Figura 2b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 3a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2019. A Figura 3b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2019 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Consumo2019.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ProporçãoConsumo2019.svg?raw=true) |
|:--:|:--:|
| Figura 3a: Consumo Ponta e Fora da Ponta | Figura 3b: Percentual de Consumo Ponta e Fora da Ponta |

### Custo da Energia Consumida

A Figura 4a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2017. A Figura 4b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2017 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,1508 e no período fora de ponta este valor custou em média R$ 0,3207.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Custos2017.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Proporção2017.svg?raw=true) |
|:--:|:--:|
| Figura 4a: Consumo Ponta e Fora da Ponta | Figura 4b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 5a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2018. A Figura 5b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2018 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,2653 e no período fora de ponta este valor custou em média R$ 0,3530.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Custos2018.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Proporção2018.svg?raw=true) |
|:--:|:--:|
| Figura 5a: Consumo Ponta e Fora da Ponta | Figura 5b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 6a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2019. A Figura 6b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2019 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,3427 e no período fora de ponta este valor custou em média R$ 0,3900.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Custos2019.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Proporção2019.svg?raw=true) |
|:--:|:--:|
| Figura 6a: Consumo Ponta e Fora da Ponta | Figura 6b: Percentual de Consumo Ponta e Fora da Ponta |

A partir das Figuras 1a-6b é possível observar que a energia consumida no período de ponta é inferior a 10% em todos os meses analisados, o que indica uma potencial preocupação com a gestão do consumo de energia nesse período. Apesar de a energia consumida no período de ponta representar menos de 10%, esta contribui com aproximadamente 25% dos custos mensais totais. Nota-se também que de um ano para outro ocorre uma elevação tanto nas tarifas do período de ponta quanto fora da ponta. De forma geral, nos três anos estudados a tarifa no período de ponta é aproximadamente quatro vezes maior do que a tarifa no período fora de ponta.
            
## Análise de Reativos
Nesta subseção tem por objetivo realizar uma análise de reativos de nossa unidade de carga, em uma primeira etapa a medição do fator de potência deve ser avaliada, podendo ser obtida de duas formas: Avaliação horária e Avaliação mensal [5]

### Avaliação horária
O fator de potência será calculado através dos valores de potência/energia ativa e reativa medidos a cada intervalo de 1 hora, durante o período de faturamento considerando os postos tarifários (Horário de ponta e fora de ponta).

Para o cálculo do fator de potência avaliado de hora em hora, foram utilizados os dados de demanda de potência ativa e reativa durante o período de 2017 a 2019, que possuem registro a cada 15 minutos. O valor considerado do fator de potência para uma determinada hora foi determinado como a média dos dados entre uma hora e outra. Os resultados obtidos foram ilustrados nas Figuras 7a-c

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/2017_Diario_Reativos.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/2018_Diario_Reativos.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/2019_Diario_Reativos.svg?raw=true) |
|:--:|:--:|:--:|
| Figura 7a: Curva do Fator de Potência 2017 | Figura 7b: Curva do Fator de Potência 2018 |Figura 7c: Curva do Fator de Potência 2019 |


As Figuras 7a-c mostram as curvas do fator de potência durante um dia para durante o período de 2017 a 2019, respectivamente. O horário de ponta é das 17h30 às 20h30 conforme estipulado pelo posto de tarifação da concessionária Light[2], que está marcada com uma caixa roxa. Observa-se que os valores de fator de potência obtidos na faixa de 6:30 a 23:59 horas estão abaixo do valor 0,90. Em particular, verifica-se que às sextas-feiras e sábados são obtidos os valores mínimos de fator de potência, sendo o valor mínimo 0,663 obtido em 2018. Por outro lado, na faixa dos horários de ponta, obteve-se um fator de potência mínimo de 0,727 em. 2018. Essa análise verifica se os valores de fator de potência estão abaixo do valor limite mínimo de 0,92 de acordo com a legislação brasileira (PRODIST – Módulo 8 e ANEEL Res. 414)[3]

### Avaliação mensal
O fator de potência será calculado através de valores de potência/energia ativa e reativa medidos para o período de faturamento (tarifa convencional).

Para o cálculo do fator de potência por mês, foram utilizados os dados de demanda de potência ativa e reativa durante o período de 2017 a 2019, que possuem registro a cada 15 minutos. O valor considerado do fator de potência para uma determinado mês foi determinado como a média dos dados do mês correspondente. Os resultados obtidos foram ilustrados na Figura 8

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/FP_Mensal.svg?raw=true) | 
|:--:|
| Figura 8: Fator de Potência Mês/Ano - Avaliação Mensal | 

Na Figura 8 são apresentados os valores de fator de potência obtidos nos diferentes meses do ano durante o período de 2017 e 2019. Pode-se observar que os valores de fator de potência estão abaixo do valor limite mínimo de 0,92 de acordo com a legislação brasileira. Sendo o valor mais crítico de 0,798 ocorreu no mês de fevereiro de 2018.

### Faturamento da Energia Reativa Excedente

Existem dois tipos de faturamento de energia reativa excedente: avaliação horária e avaliação mensal do fator de potência [1]. No primeiro caso, considera-se para cada posto de tarifação, ou seja, horários de pico e fora de pico, para os quais são necessários os valores de fator de potência registrados em cada hora, conforme á llegislação brasileira. Por outro lado, na a avaliação mensal é considerada apenas uma tarifa convencional avaliada a cada mês. Para o nosso estudo de caso, a concessionária Light inclui o faturamento do excesso de energia reativa calculada com a avaliação horária na conta de energia.

A seguir, são apresentados os gráficos de barras do faturamento do excedente de energia reativa [R\$], obtidos nas contas mensais de energia durante o período de 2017 a 2019:

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ExcedenteReativos2017.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ExcedenteReativos2018.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ExcedenteReativos2019.svg?raw=true) |
|:--:|:--:|:--:|
| Figura 9a: Facturamento da Energia Reativa Excedente 2017 | Figura 9b: Facturamento da Energia Reativa Excedente 2018 |Figura 9c: Facturamento da Energia Reativa Excedente 2019 |

Nas Figuras 9a-c mostram os custos devido ao excedente de potência reativa durante o período de 2017 a 2019. Observando que os custos nas horas fora de ponta são maiores que as horas de ponta, isso faz sentido já que o horário de ponta só cobre 03 horas por dia. Os valores médios e totais calculados são apresentados na Figura 10a. Adicionalmente, o comportamento do faturamento total por mês e em seu respectivo ano pode ser visualizado na Figura 10b.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/Resumo_FER.PNG?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/assets/ExcedenteReativosResumo.svg?raw=true) | 
|:--:|:--:|
| Figura 10a: Facturamento da Energia Reativa Excedente Total |Figura 10b: Facturamento da Energia Reativa Excedente Total |


### Medidas para Redução de Custo por Energia Reativa Excedente
Nesta subseção, descreveremos algumas medidas para reduzir o custo da energia reativa excedente[5], uma vez que foi verificado que nossa unidade de carga (CT) estudada possui um fator de potência abaixo do valor mínimo.

#### Substituição de equipamentos por outros mais eficientes: 
É a readequação do sistema de iluminação e climatização, até a substituição dos motores por outros mais eficientes, existem várias tecnologias no mercado para melhorar a eficiência.

#### Correção do fator de potência:
As primeiras medidas que se deve aplicar para correção de baixo fator de potência são aquelas relacionadas às condições operacionais e as características dos equipamentos. Ou seja, dentro do possível, atacar as causas raízes: motores operando em vazio (sem carga mecânica), motores super dimensionados, transformadores operando em vazio ou com pequenas cargas, transformadores super dimensionados, nível de tensão acima da nominal e grande quantidade de motores de pequena potência; que levam a esse baixo fator de potência.

Outra forma de se realizar a correção do fator de potência é por meio de capacitores estáticos, o que constitui a solução mais prática, e em geral é a mais adotada.

#### Sistemas de Gestão da Energia:
São os processos necessários para melhorar o desempenho de energia, incluindo eficiência, uso, consumo e intensidade da energia. Almeja-se com essa norma reduções nos custos de energia, nas emissões de gases do efeito estufa e em outros impactos ambientais, por meio da gestão sistemática da energia.

# Conclusões

No presente trabalho as análises preliminares foram abordadas como: Análise do consumo de energia, análise de Demanda, análise de reativos e e análise de crescimento de nossa unidade de carga escolhida (Centro Tecnológico da Universidade Federal do Rio de Janeiro), podendo-se concluir o seguinte: 

Na análise de consumo, os resultados obtidos evidenciam a necessidade de se implantar uma prática de economia de gastos com energia elétrica buscando consumir o mínimo possível em períodos de ponta, conduzindo a unidade consumidora a uma redução nos gastos com energia elétrica.

Na análise de reativos, foi verificado que nossa unidade de carga (CT/UFRJ) possui fator de potência abaixo do valor mínimo de acordo com a legislação brasileira. Portanto, é necessário tomar medidas para a correção do fator de potência. Este trabalho não tem como objetivo avaliar quais medidas seriam as melhores, porém, elas poderiam ser estudadas para a próxima etapa.

# Trabalhos Futuros

A próxima etapa deste trabalho apresentará um estudo de viabilidade de migração para o Mercado Livre, utilizando preferencialmente técnicas de Data Science, Machine Learning, Forecasting, entre outras, para fundamentar a sua análise e corroborar a possibilidade da migração.

# Referências
[1] ANEEL. RESOLUÇÃO NORMATIVA Nº 414. 11. ed. [S.l.]: AGÊNCIA NACIONAL DE ENERGIA ELÉTRICA, 2010.

[2] ANEEL. Postos Tarifários. 2020. [Online; accessed 12-Dezembro-2020]. Disponível em: <www.aneel.gov.br/postos-tarifarios>.

[3] ANEEL. Procedimentos de Distribuição de Energia Elétrica no Sistema Elétrico Nacional– PRODIST. 11. ed. [S.l.]: Módulo 8 – Qualidade da Energia Elétrica, 2020.

[4] FILHO, J. Instalacoes eletricas industriais. Livros Tecnicos e Cientificos, 2002.ISBN 9788521612865. Disponível em: <https://books.google.com.br/books?id=Bk5LAAAACAAJ>.

[5] SILVA, D. M. Análise Qualitativa de Medidas para Redução de Custos Industriais com Energia Elétrica. Dissertação (TCC) — Universidade de São Paulo, Escola de Engenharia de São Carlos, Brasil, 2012.
