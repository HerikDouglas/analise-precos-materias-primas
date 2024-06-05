# Análise de Preços de Matérias-Primas :male_detective:


## Introdução :memo:

Este projeto foi desenvolvido sob a orientação de um professor, tem como objetivo analisar a evolução dos preços de 12 matérias-primas ao longo dos anos de 1920-2020. O [código Python](https://github.com/HerikDouglas/analise-precos-materias-primas/blob/main/projeto_analise_materia_prima.ipynb) utiliza bibliotecas como Pandas, Matplotlib e Seaborn para explorar os dados, identificar padrões e responder a cinco perguntas específicas.
Este repositório contém os seguintes arquivos:
* `README.md`:(este arquivo que você está lendo) contém uam descrição do projeto, ferramentas e algumas outras informações;
* `agricultural_raw_material.csv`: Contém o arquivo CSV com os dados históricos de preços.
* `projeto_analise_materia_prima.ipynb`: Este arquivo contém o código Python principal para análise dos dados.

## Ferramentas e Tecnologias Utilizadas :hammer_and_wrench:
* **[Python](https://www.python.org/):** para manipulação e análise de dados.
* **Bibliotecas:** [numpy](https://numpy.org/pt/), [pandas](https://pandas.pydata.org/), [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/)
* **[Google Colab](https://colab.google/):** ambiente de desenvolvimento e execução dos códigos.
* **[GitHub](https://github.com/HerikDouglas):** para versionamento e compartilhamento do código.

## Dados :bar_chart:
O conjunto de dados utilizado neste projeto ([agricultural_raw_material.csv](https://github.com/HerikDouglas/analise-precos-materias-primas/blob/main/agricultural_raw_material.csv)) foi obtido da plataforma de desafios de data science [Kaggle](https://www.kaggle.com/datasets/kianwee/agricultural-raw-material-prices-19902020/data). Ele contém informações mensais sobre os preços e a taxa de variação percentual de 12 matérias-primas:

* Lã Grossa (Coarse wool) 
* Copra
* Algodão (Cotton)
* Lã Fina (Fine wool)
* Tora Dura (Hard log)
* Madeira Serrada dura (Hard sawnwood)
* Couro (Hide)
* Madeira Compensada (Plywood)
* Borracha (Rubber)
* Madeira em Toras Macias (Softlog)
* Madeira Serrada Macia (Soft sawnwood)
* Polpa de Madeira (Wood pulp)

## Pré-processamento :gear:
O código realiza um pré-processamento cuidadoso dos dados, incluindo:

* **Remoção de caracteres especiais:** %, "," e "-".
* **Tratamento de valores ausentes:** NaN e "MAY90".
* **Conversão para tipo float:** colunas de preços e taxa de variação.
* **Formatação da coluna de data:** como índice datetime para facilitar a análise temporal.

## Análise Exploratória :mag_right:
* **Visualização de informações básicas do DataFrame:** `usando df.head()` e `df.info()`.
* **Verificação de valores nulos:** `usando df.isnull().sum()`.
* **Análise descritiva:** medidas de resumo como média, mediana, mínimo e máximo para cada matéria-prima.
* **Visualização de distribuições de frequência:** usando histogramas para cada matéria-prima.
* **Análise de correlações:** utilizando mapas de calor para correlações entre preços e entre taxas de variação.
* **Comparação de preços ao longo do tempo:** usando gráficos de linha para cada matéria-prima.

## Respondendo às perguntas :grey_question:
Respondendo às Perguntas:

**1. Qual a variação normal do preço de cada matéria-prima?**

* A maioria das matérias-primas apresentou maior quantidade de variação em até 5%.
* Madeira serrada dura teve a menor taxa de variação, entre 0% e 5%.
* Essa informação pode ser útil para investimentos, indicando matérias-primas com menor volatilidade.
  
**2. Encontre a matéria-prima que tem o menor preço ao longo dos anos.**

* Algodão e borracha apresentaram os menores preços em geral.
* Um gráfico comparativo entre as duas matérias-primas revelou que o algodão teve o menor preço na maioria dos anos.
 
**3. Qual matéria-prima tem a maior e menor variação de % de preço?**

* Madeira Serrada Macia teve a maior variação percentual, acima de 60%.
* Madeira Compensada teve a menor variação percentual, abaixo de 20%.
 
**4. Encontre as matérias-primas com mudança drástica de preço.**

* Lã Fina (alto preço) e Tora Dura (baixo preço) apresentaram mudanças drásticas de preço.
* Gráficos de dispersão para preços altos e baixos revelaram essas mudanças.

**5. Descobrir a faixa de preço de matérias-primas de baixo preço:**

* Algodão: Mediana próxima a US$2, com outliers até US$4.
* Couro: Mediana por volta de US$75, com outliers abaixo de US$50.
* Softlog: Mediana próxima a US$150, com outliers perto de US$250.
* Tora dura: Mediana um pouco acima de US$200, com outliers acima de US$400.
* Madeira Serrada Macia: Mediana perto de US$300, com outliers próximos a US$200.
* Borracha: Mediana abaixo de US$2.5, com outliers acima de US$4.

## Visualizações :monocle_face:

O código gera diversos gráficos e mapas de calor para ilustrar as análises, incluindo:

* Gráficos de linha para preços e taxas de variação.
* Histogramas para distribuições de frequência.
* Mapas de calor para correlações.

## Trabalhos a serem feitos e contribuições :handshake:
Umas das possibilidades a serem desenvolvidas neste projeto diz respeito a previsão de preços a partir da análise dos preços. Sinta-se à vontade para contribuir com este projeto abrindo issues ou enviando pull requests com sugestões de melhorias ou novas funcionalidades.

## Licença :white_check_mark:
Este projeto está licenciado sob a licença [GPL 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

## Contato 📭
<div>

<a href="https://instagram.com/herikdouglas.20" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/herik-douglas-oliveira-reinaldo-615881269" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
[![Email](https://img.shields.io/badge/Email-cdcdouglas428@gmail.com-blue)](mailto:cdcdouglas428@gmail.com)
</div>
