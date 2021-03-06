# Projeto `AVALIAÇÃO DA MIGRAÇÃO DE UNIVERSIDADE FEDERAL DE SÃO CARLOS PARA O MERCADO LIVRE DE ENERGIA.`
## Project `EVALUATION OF THE MIGRATION OF THE FEDERAL UNIVERSITY OF SÃO CARLOS FOR THE FREE ENERGY MARKET.`
### IT304S - Contratação de Energia para Grandes Consumidores



### Professor: Dr. Luiz Carlos Pereira da Silva
### Professor: MSc. Lia Farias



## Descrição Resumida do Projeto

A Universidade Federal de São Carlos possui 4 Unidades Consumidoras, as unidades de São Carlos e Sorocaba trabalham com a conceição da CPFL, e as unidades de Araras e Lagoa do Sino com Elektro. Todas dentro do Grupo A4.

Neste projeto se estuda o consumo de 3 UC, com dados recoletados das faturas e tabelas fornecidos pelo time do curso, para assim avaliar a possibilidade da migração da UFSCAR para o mercado livre de energia.


## Abstract

The Federal University of São Carlos has 4 Consumer Units, the São Carlos and Sorocaba units work with the concept of CPFL, and the Araras and Lagoa do Sino units with Elektro. All within the A4 Group.

In this project, the consumption of 3 UCs is studied, with data collected from the invoices and tables provided by the course team, in order to evaluate the possibility of migration from UFSCAR to the energy free market.


## Equipe

* Leandro A. Arias Galicia,       RA: 228967
* Jose Roberto dos Santos Junior, RA: 261721
* Robson F. Santos Junior,        RA: 232833


## Vídeo do Projeto

https://www.youtube.com/watch?v=LwBuVdcCWZ4&feature=youtu.be

## Perguntas de Pesquisa

 O Mercado Livre de Energia é um ambiente competitivo de negociação de energia elétrica em que os participantes podem negociar livremente todas as condições comerciais como fornecedor, preço, quantidade de energia contratada, período de suprimento, pagamento, entre outras. O Mercado Livre é um ambiente de negociação onde consumidores “livres” podem comprar energia alternativamente ao suprimento da concessionária local. Nesse ambiente, o consumidor negocia o preço da sua energia diretamente com os agentes geradores e comercializadores. Dessa forma, o cliente livre pode escolher qual será o seu fornecedor de energia. Diante o nosso contexto, neste projeto vamos analisar a viabilidade de migração da UFSCAR para o Mercado Livre através da busca das respostas das seguintes perguntas metodologicas:

### Analise Previa:

* A Demanda Contratada está adequada? Se não, qual deveria ser a contratação?
* Há excesso de reativos? É necessário fazer correção do fator de potência da instalação?
* Existe tendência de crescimento no consumo de energia? E na Demanda Registrada?

### Estudo de Viabilidade de Migração para o Mercado Livre.

* Vale a pena migrar para o Mercado Livre? tem estrutura e demanda suficiente?
* Qual a recomendação para uma contratação?


## Objetivos do projeto
~~~
Análise das contas de energia das unidades da UFSCAR, são quatro campos universitários para avaliar a viabilidade de mudança do mercado cativo de energia para o mercado livre.
~~~

## Recursos e Métodos

Contas de energia, planilhas disponibilizadas pela Unicamp. Plataformas GitHub e Colab.

## Bases de Dados

`<Elencar bases de dados utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 1 | Planilhas disponibilizadas pela Unicamp | `Planilhas com os dados das unidades consumidoras disponibilizadas pela Unicamp.`
Base 2 | Contas de energia disponibilizadas pela Unicamp | `Contas de energia das unidades consumidoras disponibilizadas pela Unicamp.`

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | github.com | `Ferramenta para gerenciamento de arquivos e disponibilidazação de dados.`
Ferramenta 2 | colab.com | `Ferramenta para tratamento e análise de dados, lincada ao Github.`

## Metodologia

CRISP DM é a abreviação de Cross Industry Standard Process for Data Mining que, trazendo para o português, pode ser entendida como processo padrão da indústria cruzada para mineração de dados. Essa é uma metodologia capaz de transformar os dados da empresa em conhecimento e informações de gerenciamento.

A metodologia CRISP DM define o ciclo de vida do projeto, dividindo-o em seis etapas, que vamos conhecer agora:

* Business Understanding: Definição dos objetivos, declaração do problema, pergunta de interesse.
* Data Understanding: Utilização de nosso conhecimento para coletar os dados.
* Data Preparation: Manipulação de dados para a eliminação de outliers e dados faltantes.
* Modeling: Modelo ou abordagem utilizado para estudar o comportamento de nosso sistema a partir de nossos dados.
* Evaluation: Avaliação dos resultados obtidos, no contexto se são de ajuda para responder nossa pergunta de interesse.
* Deployment: Disponibilizar o análise de dados.

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

## Resultados e Discussão

Todas as avaliações feitas no que se diz respeito às faturas de energia dos campos independentemente da região ou da fornecedora de energia, observa-se uma grande carência no quesito controle, avaliação, monitoração, desempenho e desenvolvimento das unidades, estando sendo muitas das vezes penalizadas com relação a índices de energia reativa e também no que se diz respeito referente às demandas contratadas e registradas.

Os campus devem receber auxílio ou se preparar para melhorar suas atenções com relação a seus consumos.

Quanto a migração para o mercado livre de energia, conforme expressado pelo grupo, há uma dificuldade muito grande de avaliar a gestão da universidade por uma equipe contratada de consultoria, uma equipe interna ou até mesmo “educar” sobre o tema criar uma disciplina para que esta gestão possa ser feita como matéria evolutiva dentro do curso de engenharia, fazendo com que este controle seja feito de forma natural e evolutivo assim como possa treinar já alunos de graduação para este mercado de trabalho.

Todos os campos estudados possuem viabilidade para a migração para o mercado livre de energia, o campos com maior facilidade decorrente da demanda de consumo são as unidades consumidoras do campus de São Carlos, com ambos superando a demanda mínima de 500 kW exigida para a migração. Os demais campus não atingem esta demanda, porém, podem ser integrados como uma única carga levando assim a disponibilidade também de acesso ao mercado livre de energia

