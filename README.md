Trabalho para disciplina Introdução a python - Ciencia de Dados.
===

Projeto de T2 - O Conjunto de Dados de Admissões de Pós-Graduação de Berkeley em 1973.
===

Levanta questões centrais sobre a equidade nos processos seletivos em instituições de ensino superior. Os dados, à primeira vista, indicam uma desigualdade de gênero nas admissões, sugerindo que mulheres tinham menor probabilidade de serem aceitas em comparação aos homens. Essa evidência inicial gerou um debate sobre a possibilidade de discriminação institucional contra mulheres no ambiente acadêmico

Atividade
===

Desenvolver uma análise exploratória de dados que identifique padrões e propondo interpretações sobre viés e desigualdade na admissão de pós-graduação da Universidade de
Berkeley em 1973.

Tabela de conteúdos
---
<!--ts-->   
   * [Tecnologias](#🛠-tecnologias-utilizadas)
   * [Criação Virtualenv](#criação-virtualenv)
   * [Instalação Pacotes](#instalação-de-pacotes)
   * [Acessando Virtualenv](#acessando-virtualenv---wsl-linux)
   * [Código](#código)
     * [Pre Processamento](#pré-processamento)
     * [Analise dos Dados](#analise-dos-dados)
     * [Questionamentos](#questionamentos)
   * [Referências](#referências)
   * [Contribuição](#contribuição)
   * [Autor](#autores)
   * [Licença](#licença)
<!--te-->

🛠 Tecnologias Utilizadas
---
As seguintes ferramentas foram usadas na construção do projeto:

- [Python 3.13.0](https://docs.python.org/pt-br/3/)
- [Pandas 2.2.3](https://pandas.pydata.org/docs/)
- [matplotlib 3.10.0](https://matplotlib.org/stable/index.html)
- [seaborn 0.13.2](https://seaborn.pydata.org/tutorial.html)


Criação Virtualenv
---


~~~bash
python3 -m venv .venv
~~~


Acessando Virtualenv - WSL, Linux
---


~~~bash
source .venv/bin/activate
~~~


Acessando Virtualenv - Windows
---


~~~bash
.venv/Scripts/activate.bat
~~~


Instalação de Pacotes
---


~~~bash
python -m pip install -r requirements.txt
~~~


Código
---

### Pré Processamento

* Onde deu inicio a analise exploratória, no arquivo **01_pre_processamento.ipynb** no diretório **notebooks**,contem um jupyter notebook onde todos os passos abaixo estão contidos e finaliza o pré processamento. 
    
    1. Carregar o dataset;
    2. Verificar suas informações gerais;
    3. Verificar dados ausentes;
    4. Verificar e remover outliers;
    5. Verificar e corrigir inconsistências;
    6. Criar novas variáveis derivadas das existentes;
    7. Converter tipos de dados;
    8. Salvar o dataset pré-processado

### Analise dos Dados

* No arquivo **02_analise_dados.ipynb** no diretório **notebooks** contem um jupyter notebook, onde todos os passos abaixo estão contidos, foi utilizado tecnicas de agrupamentos para evidenciar, comparar, analisar distribuições, examinar estatiticas, identificar corelações entre outros aspectos pedidos, utilizando alguns gráficos de barra, pizza e linha para enfatizar os ponto necessários.

    1. Carregar o dataset e verificar suas informações gerais;
    2. Examinar as estatísticas descritivas das variáveis numéricas, verificando médias, medianas, desvios padrão, mínimos e máximos.
    3. Analisar a distribuição de frequências das variáveis categóricas.
    4. Verificar a representatividade de homens e mulheres nas aplicações e admissões por departamento.
    5. Comparar o número total de candidatos (admitidos e rejeitados) por gênero.
    6. Comparar as taxas de admissão por departamento e gênero.
    7. Comparar as taxas de admissão agregadas e desagregadas por departamento.
    8. Verificar a relação entre o número de candidatos e as taxas de admissão/rejeição por gênero e departamento.
    9. Comparar as taxas de admissão agregadas para homens e mulheres.
    10. Analisar como as taxas de admissão de homens e mulheres variam entre os departamentos.
    11. Identificar quais departamentos têm as maiores e menores taxas de rejeição.
    12. Avaliar a proporção de inscrições feitas por homens e mulheres nos departamentos mais e menos competitivos.
    13. Comparar as taxas de admissão gerais com as taxas de admissão por departamento.
    14. Verificar se existem preferências de departamentos por gênero que podem influenciar os resultados observados.


### Questionamentos

* No arquivo **03_questionamentos.ipynb** no diretório **notebooks** contem um notebook python e onde todos os questionamentos foram respondidos.

    1. Há departamentos ou gêneros que apresentam taxas de admissão ou rejeição desproporcionalmente altas ou baixas?
    2. Há equilíbrio na distribuição de gêneros nos departamentos?
    3. Como os padrões de admissão diferem entre os departamentos e gêneros?
    4. Existe um viés aparente contra algum gênero?
    5. Há departamentos mais favoráveis a um gênero específico?
    6. Quais departamentos são mais competitivos e como isso afeta os gêneros?
    7. Como as conclusões mudam ao desagregar os dados por departamento?
    8. Justifique o viés de gênero nas admissões de pós-graduação de Berkeley.


### Referências
---

- [Python Documentação](https://docs.python.org/pt-br/3/)
- [Pandas Documentação](https://pandas.pydata.org/docs/)
- [matplotlib Documentação](https://matplotlib.org/stable/index.html)
- [seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

### Contribuições
---

- Divanilza Ferreira Flexa
- Emerson da Silva Maciel
- Isabele Benevinuto Sabóia
- Victor Lamark Costa Brasil
- Wagner da Costa Oliveira

### Autores
---

- Divanilza Ferreira Flexa
- Emerson da Silva Maciel
- Isabele Benevinuto Sabóia
- Victor Lamark Costa Brasil
- Wagner da Costa Oliveira

### Licença
---

- [GNU General Public License (GPL)](https://www.gnu.org/licenses/gpl-3.0.html)