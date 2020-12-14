https://mybinder.org/v2/gh/156449/IT304---Grupo-5.git/HEAD

# IT304 - Tópicos em Sistemas de Energia Elétrica I <br/> Comercialização de Energia Elétrica para Grandes Clientes

# Projeto: Pré-análise das Faturas - UFRJ/Centro de Tecnologia

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
~~~
<Perguntas de pesquisa que o projeto pretende responder ou hipóteses a serem avaliadas, enunciadas de maneira objetiva e verificável.>
~~~
Este estudo tem como objetivo realizar diferentes análises preliminares para determinar a possibilidade de migração de um contrato de energia elétrica do Ambiente de Contratação Regulada para o Ambiente de Contratação Livre (ACR/ACL) como medida econômica. Esta análise está limitada ao Centro de Tecnologia da UFRJ, unidade consumidora escolhida para análise.

## Objetivos do projeto
~~~
<Como seu projeto propôs abordar o problema apresentado.>
~~~
Os objetivos deste estudo se resumem em verificar se há a possibilidade de migração de um contrato de energia elétrica do Ambiente de Contratação Regulada para o Ambiente de Contratação Livre (ACR/ACL) para a unidade consumidora escolhida. Para tal, serão realizadas análises acerca da qualidade dos dados disponíveis, como por exemplo se há ou não a ausência de faturas. Em seguida, serão realizadas análises buscando identificar o perfil de consumo da unidade consumidora em questão considerando o consumo nos períodos de ponta e fora da ponta, além de uma análise dos custos decorrentes deste perfil de consumo. Serão realizadas também análises sobre a demanda contratada, buscando identificar se esta está adequada para a unidade consumidora em questão ou se há a necessidade de uma revisão da demanda contrada. Por fim, serão realizadas análises sobre o fator de potência da unidade consumidora, buscando identificar se o fator de potência esta dentro dos limites estabelcidos pelas normas ou se há a necessidade da realização da correção do fator de potência da instalação. Todas as análises serão realizadas para os anos de 2017, 2018 e 2019.

# Recursos e Métodos

## Bases de Dados
`<Elencar bases de dados utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ano de 2017 | https://drive.google.com/file/d/1nAatA3B2JmC2uIUY10GiAe9smT-1Q2Cc/view?usp=sharing | Faturas Digitalizadas para o ano de 2017.
Ano de 2018 | https://drive.google.com/file/d/1VvRmQD-MoJczpMMejnxBmGbnM0nYHPMo/view?usp=sharing | Faturas Digitalizadas para o ano de 2018.
Ano de 2019 | https://drive.google.com/file/d/17Gyi0AzNh-rDwgOLgIPcGGlBRSPz0wwe/view?usp=sharing | Faturas Digitalizadas para o ano de 2019.

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Google Sheets | https://www.google.com/sheets/about/ | Ferramenta para construção de planilhas de dados online. Usada para digitalizar as faturas de energia.
Jupyter Notebook | https://jupyter.org/ | Editor Python no formato Notebook. Usada para gerar as curvas/gráficos apresentados no trabalho.

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~

## Detalhamento do Projeto
~~~
<Apresente aqui detalhes da análise. Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.

Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.>
~~~

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~
## Análise do Consumo de Energia

### Consumo de Energia

A Figura 1a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2017. A Figura 1b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2017 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Consumo2017.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/ProporçãoConsumo2017.svg?raw=true) |
|:--:|:--:|
| Figura 1a: Consumo Ponta e Fora da Ponta | Figura 1b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 2a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2018. A Figura 2b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2018 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Consumo2018.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/ProporçãoConsumo2018.svg?raw=true) |
|:--:|:--:|
| Figura 2a: Consumo Ponta e Fora da Ponta | Figura 2b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 3a apresenta o total mensal de energia consumida, em MWh, nos períodos de ponta e nos períodos fora de ponta para o ano de 2019. A Figura 3b apresenta, de forma proporcional, qual a contribuição da energia consumida nos períodos de ponta e fora de ponta para a energia total consumida por mês nesse mesmo ano. Pode ser observado que em todos os meses do ano de 2019 a energia consumida no período de ponta foi inferior a 10\% da energia total consumida naquele mês

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Consumo2019.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/ProporçãoConsumo2019.svg?raw=true) |
|:--:|:--:|
| Figura 3a: Consumo Ponta e Fora da Ponta | Figura 3b: Percentual de Consumo Ponta e Fora da Ponta |

### Custo da Energia Consumida

A Figura 4a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2017. A Figura 4b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2017 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,1508 e no período fora de ponta este valor custou em média R$ 0,3207.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Custos2017.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Proporção2017.svg?raw=true) |
|:--:|:--:|
| Figura 4a: Consumo Ponta e Fora da Ponta | Figura 4b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 5a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2018. A Figura 5b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2018 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,2653 e no período fora de ponta este valor custou em média R$ 0,3530.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Custos2018.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Proporção2018.svg?raw=true) |
|:--:|:--:|
| Figura 5a: Consumo Ponta e Fora da Ponta | Figura 5b: Percentual de Consumo Ponta e Fora da Ponta |

A Figura 6a apresenta os custos mensais da energia consumida, em R$, nos períodos de ponta e fora da ponta para o ano de 2019. A Figura 6b apresenta o percentual dos custos totais mensais de energia consumida considerando os períodos de ponta e fora de ponta para esse mesmo ano. Pode ser observado que em todos os meses do ano de 2019 o custo da energia consumida no período de ponta representa aproximadamente 25% dos custos totais com a energia consumida naquele mês. Vale ressaltar que nesse ano o kWh no período de ponta custou em média R$ 1,3427 e no período fora de ponta este valor custou em média R$ 0,3900.

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Custos2019.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/Proporção2019.svg?raw=true) |
|:--:|:--:|
| Figura 6a: Consumo Ponta e Fora da Ponta | Figura 6b: Percentual de Consumo Ponta e Fora da Ponta |

A partir das Figuras 1a-6b é possível observar que a energia consumida no período de ponta é inferior a 10% em todos os meses analisados, o que indica uma potencial preocupação com a gestão do consumo de energia nesse período. Apesar de a energia consumida no período de ponta representar menos de 10%, esta contribui com aproximadamente 25% dos custos mensais totais. Nota-se também que de um ano para outro ocorre uma elevação tanto nas tarifas do período de ponta quanto fora da ponta. De forma geral, nos três anos estudados a tarifa no período de ponta é aproximadamente quatro vezes maior do que a tarifa no período fora de ponta.
            
## Análise de Reativos
Nesta subseção tem por objetivo realizar uma análise de reativos de nossa unidade de carga, em uma primeira etapa a medição do fator de potência deve ser avaliada, podendo ser obtida de duas formas: Avaliação horária e Avaliação mensal

### Avaliação horária
O fator de potência será calculado através dos valores de potência/energia ativa e reativa medidos a cada intervalo de 1 hora, durante o período de faturamento considerando os postos tarifários (Horário de ponta e fora de ponta).

Para o cálculo do fator de potência avaliado de hora em hora, foram utilizados os dados de demanda de potência ativa e reativa durante o período de 2017 a 2019, que possuem registro a cada 15 minutos. O valor considerado do fator de potência para uma determinada hora foi determinado como a média dos dados entre uma hora e outra. Os resultados obtidos foram ilustrados nas Figuras 7a-c

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/2017_Diario_Reativos.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/2018_Diario_Reativos.svg?raw=true) | ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/2019_Diario_Reativos.svg?raw=true) |
|:--:|:--:|:--:|
| Figura 7a: Curva do Fator de Potência 2017 | Figura 7b: Curva do Fator de Potência 2018 |Figura 7c: Curva do Fator de Potência 2019 |


As Figuras 7a-c mostram as curvas do fator de potência durante um dia para durante o período de 2017 a 2019, respectivamente. O horário de ponta é das 17h30 às 20h30 conforme estipulado pelo posto de tarifação da concessionária Light  \cite{ANEEL_1}, que está marcada com uma caixa roxa. Observa-se que os valores de fator de potência obtidos na faixa de 6:30 a 23:59 horas estão abaixo do valor 0,90. Em particular, verifica-se que às sextas-feiras e sábados são obtidos os valores mínimos de fator de potência, sendo o valor mínimo 0,663 obtido em 2018. Por outro lado, na faixa dos horários de ponta, obteve-se um fator de potência mínimo de 0,727 em. 2018. Essa análise verifica se os valores de fator de potência estão abaixo do valor limite mínimo de 0,92 de acordo com a legislação brasileira (PRODIST – Módulo 8 e ANEEL Res. 414)

### Avaliação mensal
O fator de potência será calculado através de valores de potência/energia ativa e reativa medidos para o período de faturamento (tarifa convencional).

Para o cálculo do fator de potência por mês, foram utilizados os dados de demanda de potência ativa e reativa durante o período de 2017 a 2019, que possuem registro a cada 15 minutos. O valor considerado do fator de potência para uma determinado mês foi determinado como a média dos dados do mês correspondente. Os resultados obtidos foram ilustrados na Figura 8

| ![alt text](https://github.com/156449/IT304---Grupo-5/blob/main/FP_Mensal.svg?raw=true) | 
|:--:|
| Figura 8: Fator de Potência Mês/Ano - Avaliação Mensal | 

# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~
No presente trabalho as análises preliminares foram abordadas como: Análise do consumo de energia, análise de Demanda, análise de reativos e e análise de crescimento de nossa unidade de carga escolhida (Centro Tecnológico da Universidade Federal do Rio de Janeiro), podendo-se concluir o seguinte: 

Na análise de consumo, os resultados obtidos evidenciam a necessidade de se implantar uma prática de economia de gastos com energia elétrica buscando consumir o mínimo possível em períodos de ponta, conduzindo a unidade consumidora a uma redução nos gastos com energia elétrica.

Na análise de reativos, foi verificado que nossa unidade de carga (CT/UFRJ) possui fator de potência abaixo do valor mínimo de acordo com a legislação brasileira. Portanto, é necessário tomar medidas para a correção do fator de potência. Este trabalho não tem como objetivo avaliar quais medidas seriam as melhores, porém, elas poderiam ser estudadas para a próxima etapa.

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~
A próxima etapa deste trabalho apresentará um estudo de viabilidade de migração para o Mercado Livre, utilizando preferencialmente técnicas de Data Science, Machine Learning, Forecasting, entre outras, para fundamentar a sua análise e corroborar a possibilidade da migração.

# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------




# Model for Project Presentation and Folder Structure (in Portuguese)

# Estrutura de Arquivos e Pastas

A estrutura aqui apresentada é uma simplificação daquela proposta pelo [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/). Também será aceito que o projeto adote a estrutura completa do Cookiecutter Data Science e isso será considerado um diferencial. A estrutura geral é a seguinte e será detalhada a seguir:

~~~
├── README.md          <- apresentação do projeto
│
├── data
│   ├── external       <- dados de terceiros
│   ├── interim        <- dados intermediários, e.g., resultado de transformação
│   ├── processed      <- dados finais usados para a modelagem
│   └── raw            <- dados originais sem modificações
│
├── notebooks          <- Jupyter notebooks ou equivalentes
│
├── src                <- fonte em linguagem de programação ou sistema (e.g., Orange)
│   └── README.md      <- instruções básicas de instalação/execução
│
└── assets             <- mídias usadas no projeto
~~~

Na raiz deve haver um arquivo de nome `README.md` contendo a apresentação do projeto, como detalhado na seção seguinte.

## `data`

Dados utilizados no projeto respeitadas as possíveis implicações éticas, se você tiver licença para tal e se o volume for suportado pelo Github. Você pode optar por colocar um subconjunto ilustrativo dos dados.

É importante que sejam colocados os dados originais (se for possível) para garantir a reprodutibilidade do processo. Os originais são colocados na subpasta `raw` se forem produzidos pela equipe e na subpasta `external` se forem de terceiros. Também podem ser colocados aqui dados intermediários (por exemplo, dados tratados, resumidos etc.) na pasta `interim`. Finalmente, coloque os dados finais que serviram de entrada para as suas análises na subpasta `processed`.

## `notebooks`

Código do seu projeto que pode ser executado online sem instalação de software, tal como um notebook em Jupyter ou equivalente.

## `src`

Código em alguma linguagem ou projeto em Orange, Weka e similares.

Se for código em linguagem de programação, tente organizá-lo de forma que seja simples a sua execução por terceiros, por exemplo, acrescente as bibliotecas necessárias etc. Acrescente na raiz um arquivo `README.md` com as instruções básicas de instalação e execução.

## `assets`

Qualquer mídia usada no seu projeto: vídeo, ilustrações, arquivos PDF etc.

# Modelo para Apresentação do Projeto

Este é um guia de como produzir documentação em Markdown. Para entender como criar documentos em Markdown no Github, veja o material/vídeo:
[Guia de Uso do Markdown](https://github.com/mc-unicamp/oficinas/tree/master/docs).

Vide detalhes sobre o Markdown em: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

E mais especificamente sobre tabelas em: [Organizing information with tables](https://help.github.com/en/articles/organizing-information-with-tables)

O projeto pode ser apresentado em uma das possíveis formas:
1. texto completo no arquivo `README.md`;
2. texto no arquivo `README.md` e seção de Resultados e Discussão dentro de um notebook Jupyter ou equivalente -- nesse caso, deve haver um link para se abrir o notebook na respectiva seção;
3. texto completo dentro de um notebook Jupyter ou equivalente -- nesse caso, o arquivo README.md deve conter pelo menos: o título, os componentes da equipe e um link para o notebook.

Só será aceito o uso de notebook Jupyter (ou equivalente) para apresentação do projeto ou parte dele (formas 2 e 3), se for possível executá-lo online a partir de um link sem instalação local de software.

Para todos os casos, a estrutura Markdown proposta abaixo poderá ser usada, dado que os notebooks aceitam Markdown.

Segue abaixo o modelo de como deve ser apresentado e documentado o projeto. Tudo o que for indicado entre `<...>` indica algo que deve ser substituído pelo indicado. No modelo são colocados exemplos ilustrativos, que serão substituídos pelos do seu projeto.

# Modelo para Apresentação do Projeto

# Projeto `<Título em Português>`
# Project `<Title in English>`

# Descrição Resumida do Projeto
~~~
<Descreva resumidamente o que fará o projeto. O resumo idealmente deve: apresentar o contexto; indicar o problema; apresentar a sua solução para o problema; indicar porque a sua solução é melhor do que os esforços atuais (não obrigatório); concluir com os resultados alcançados.>
~~~

# Abstract in English
~~~
<English version of the abstract.>
~~~

# Equipe
* `<nome completo>` - `<RA>`

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação
~~~
<Descrição do tema do projeto, incluindo motivação, contexto gerador e caracterização do problema. A introdução também pode apresentar iniciativas correlatas para lidar com o problema (não obrigatório) e deve introduzir de forma mais detalhada que o resumo a solução proposta e resultados alcançados. Aqui também são apresentadas as seções do projeto.>
~~~

## Perguntas de Pesquisa
~~~
<Perguntas de pesquisa que o projeto pretende responder ou hipóteses a serem avaliadas, enunciadas de maneira objetiva e verificável.>
~~~

## Objetivos do projeto
~~~
<Como seu projeto propôs abordar o problema apresentado.>
~~~

# Recursos e Métodos

## Bases de Dados
`<Elencar bases de dados utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 1 | http://base1.org/ | `<Descrição da Base 1 e para que ela foi usada no projeto.>`
Base 2 | http://base2.org/ | `<Descrição da Base 2 e para que ela foi usada no projeto.>`

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | http://ferramenta1.org/ | `<Descrição da Ferramenta 1 e para que ela foi usada no projeto.>`
Ferramenta 2 | http://ferramenta2.org/ | `<Descrição da Ferramenta 2 e para que ela foi usada no projeto.>`

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~

## Detalhamento do Projeto
~~~
<Apresente aqui detalhes da análise. Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.

Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.>
~~~

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~

# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~
