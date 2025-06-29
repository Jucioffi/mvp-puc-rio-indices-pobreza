MVP: Análise Exploratória de Dados sobre a Pobreza no Brasil (2012-2022)
Autor: Júlio Cioffi
Projeto da Pós-graduação em Ciência de Dados & Analytics da PUC-RIO

1. Visão Geral do Projeto
Este projeto consiste em uma Análise Exploratória de Dados (AED) sobre os indicadores de pobreza e extrema pobreza no Brasil, abrangendo o período de agosto de 2012 a setembro de 2022. O objetivo principal é transformar dados brutos em insights visuais e estatísticos que permitam compreender as tendências temporais, a sazonalidade e as relações entre diferentes variáveis socioeconômicas.

O notebook analise_exploratoria_pobreza_brasil_MVP.ipynb documenta todo o processo, desde a definição do problema e pré-processamento dos dados até a geração das visualizações e a extração de conclusões.

2. Fonte dos Dados
O dataset utilizado foi consolidado a partir de fontes públicas e disponibilizado neste repositório do GitHub. Ele contém dados mensais sobre o número de pessoas em situação de pobreza, extrema pobreza e vulnerabilidade, além de informações sobre a população estimada e recortes para grupos vulneráveis específicos (indígenas, quilombolas e ciganos).

Dataset Consolidado Mensal: Contém dados mensais sobre o número de pessoas em situação de pobreza, extrema pobreza e vulnerabilidade, além de informações sobre a população estimada e recortes para grupos vulneráveis específicos (indígenas, quilombolas e ciganos).

Link: https://raw.githubusercontent.com/Jucioffi/mvp-puc-rio-indices-pobreza/refs/heads/main/indices_pobreza_consolidado.csv

Dataset Consolidado Anual: Uma versão agregada dos dados, utilizada para validar tendências e a consistência da análise.
Link: https://raw.githubusercontent.com/Jucioffi/mvp-puc-rio-indices-pobreza/refs/heads/main/indices_pobreza_consolidado_anual.csv

3. Metodologia da Análise
O projeto foi estruturado seguindo as etapas clássicas de uma análise exploratória de dados:
Definição do Problema e Hipóteses: Definição do escopo da análise e levantamento de hipóteses sobre a dinâmica da pobreza;

Carregamento e Limpeza dos Dados: Importação do dataset e verificação inicial da sua estrutura, tipos de dados e ausência de valores nulos ou duplicados. A análise com a biblioteca missingno validou a integridade do dataset.;

Análise Exploratória Visual: Geração de gráficos para extrair insights, focando em três análises principais:

Matriz de Correlação: Para entender a relação entre as variáveis-chave;

Boxplot Anual: Para analisar a distribuição e a variabilidade dos dados de pobreza ao longo dos anos;

Análise Sazonal: Para identificar padrões de comportamento do índice de pobreza dentro de cada ano.

Conclusões: Extração de conclusões objetivas baseadas nos padrões e tendências observados nos dados.

4. Principais Conclusões
A análise permitiu extrair conclusões importantes sobre o comportamento da pobreza no Brasil:

Tendências Temporais e Sazonalidade: Foi identificada uma clara flutuação nos indicadores de pobreza ao longo dos anos, além de um padrão sazonal, indicando que fatores macroeconômicos e sazonais influenciam diretamente a vulnerabilidade da população.

Validade dos Indicadores: A forte correlação positiva (+0.95) entre Pobreza e Extrema Pobreza confirma a consistência interna dos dados;

Desigualdade Estrutural: A análise de correlação também revelou a relação direta entre a pobreza geral e a vulnerabilidade de grupos específicos (indígenas, quilombolas e ciganos), reforçando a tese de uma desigualdade estrutural;

Robustez dos Dados: A validação visual confirmou que o dataset está 100% completo, o que garante sua confiabilidade para futuras análises estatísticas e de modelagem.

5. Como Executar o Projeto
Copie este repositório ou faça o download do notebook.

Abra o arquivo analise_exploratoria_pobreza_brasil_MVP.ipynb em um ambiente com Python e as bibliotecas listadas (Pandas, Seaborn, Matplotlib, etc.), como o Google Colab.

O notebook pode ser executado do início ao fim, pois carrega o dataset diretamente da URL pública.
