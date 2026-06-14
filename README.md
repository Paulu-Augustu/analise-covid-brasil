📊 Dossiê COVID-19: Análise do Impacto no Brasil
Bem-vindo(a) ao repositório do Dossiê COVID-19. Este projeto nasceu com o objetivo de transformar uma base de dados complexa e extensa (com registos diários de todos os municípios brasileiros) em informações claras, visuais e diretas sobre o impacto da pandemia no Brasil ao longo dos anos.

Nesta análise, fomos além dos números brutos. O nosso foco foi investigar não apenas "onde" ocorreram mais casos, mas entender a verdadeira proporção e letalidade do vírus em relação ao tamanho da população de cada Estado.

🗄️ Fonte dos Dados
Todos os dados analisados neste projeto são oficiais e públicos, extraídos diretamente do portal do Ministério da Saúde do Brasil: https://covid.saude.gov.br/.

🎯 O que foi analisado? (Principais Visões)
Para construir este dossiê, dividimos a nossa investigação em quatro grandes pilares, traduzidos em gráficos e relatórios que você pode encontrar nos arquivos deste projeto:

1. O Impacto Absoluto (Total de Óbitos por Estado)
O que fizemos: Isolamos o último dia registado na base de dados para tirar uma "fotografia" final de quantos óbitos cada Estado acumulou.

Onde ver: Arquivo Grafico_totalObitos.png

Insight: Olhando apenas para números absolutos, o Estado de São Paulo lidera o ranking de forma isolada. No entanto, levantamos uma hipótese: será que SP lidera apenas por ser o Estado mais populoso do país? Isso levou-nos à terceira etapa da análise.

2. A Curva de Contágio (Evolução no Tempo)
O que fizemos: Somamos todos os novos casos diários do Brasil inteiro para desenhar a linha do tempo da pandemia.

Onde ver: Arquivo Grafico_CasosPorAno.png

Insight: O gráfico de linhas revela claramente os "picos" da pandemia. É possível observar os momentos críticos e as diferentes "ondas" de contágio que o país enfrentou, mostrando quando o vírus se espalhou com maior velocidade.

3. A Verdadeira Proporção (Taxa de Mortalidade por 100 mil habitantes)
O que fizemos: Esta é a principal descoberta do projeto. Cruzamos o total de óbitos com a população oficial (TCU) de cada Estado. Calculamos quantas pessoas infelizmente faleceram a cada 100 mil habitantes, colocando todos os Estados em pé de igualdade.

Onde ver: Arquivo grafico_taxaMortalidade.png

Insight: A nossa hipótese inicial confirmou-se! Quando olhamos para a proporção, São Paulo sai do topo. Os Estados do Rio de Janeiro (RJ) e Amazonas (AM) revelaram-se como os locais mais duramente atingidos pela letalidade do vírus em relação ao tamanho das suas populações.

4. O Resumo Macro (Visão Regional Anual)
O que fizemos: A pedido da Diretoria/Engenharia de Dados, consolidamos milhares de linhas de dados diários numa tabela simples, limpa e direta, que resume o total de Casos e Óbitos agrupados por Região do Brasil (Norte, Sul, Nordeste, etc.) e por Ano.

Onde ver: Arquivo dossie_covid_regiao_anual.csv

📁 Estrutura dos Arquivos neste Repositório
projeto6.ipynb: O "motor" do projeto. Aqui está todo o raciocínio analítico, limpeza de dados e criação de variáveis passo a passo.

projeto6.pdf: O documento de requisitos (o "briefing" inicial) que guiou as nossas análises.

Grafico_*.png: As imagens geradas pelas nossas análises, prontas para serem coladas em qualquer apresentação executiva.

dossie_covid_regiao_anual.csv: A base de dados final, limpa e resumida, pronta para alimentar dashboards ou outros sistemas da empresa.

🛠️ Ferramentas Utilizadas
Linguagem: Python

Manipulação de Dados: Pandas (Filtros, Limpeza, Agrupamentos, Criação de novas métricas)

Visualização de Dados (Data Viz): Seaborn e Matplotlib (Gráficos corporativos focados em facilitar a tomada de decisão).
