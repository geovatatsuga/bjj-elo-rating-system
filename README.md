# 🥋 Criando e aplicando Ranqueamento por ELO RATING no Jiu-jitsu

## 📊 

Leia no Medium : https://medium.com/@jeova.anderson/do-xadrez-ao-jiu-jitsu-usando-o-elo-rating-para-identificar-o-melhor-e-mapear-perfis-de-eca8950df773

Este projeto foi desenvolvido como uma pipeline completa de análise de dados esportivos, abrangendo as etapas de extração, tratamento e organização de grandes volumes de informações históricas sobre lutas e atletas de Jiu-Jitsu. O histórico de combates foi obtido via web scraping automatizado do BJJ Heroes, uma das maiores bases de dados do esporte, assegurando informações atualizadas e confiáveis.

O diferencial do projeto é o uso do ELO Rating, um sistema de pontuação criado originalmente para o xadrez, que permite quantificar de maneira objetiva a força e evolução de cada atleta ao longo do tempo. A cada combate, o ELO do lutador é ajustado de acordo com o resultado e o nível do oponente, tornando possível comparar desempenhos entre diferentes gerações, estilos e trajetórias.

Durante o processamento, os dados passaram por etapas de limpeza, normalização e construção de variáveis fundamentais, como taxa de vitória, número de finalizações e classificação competitiva em clusters. As análises exploratórias e as visualizações interativas foram desenvolvidas com Python, pandas, matplotlib e seaborn, proporcionando uma visão clara da progressão dos atletas e do cenário competitivo como um todo.

Com isso, o projeto permite não só identificar os grandes campeões do Jiu-Jitsu de forma quantitativa, mas também analisar rivalidades históricas, padrões de ascensão e declínio, além do impacto de diferentes estratégias de carreira. Essa abordagem transforma dados brutos em conhecimento prático e estratégico para atletas, treinadores, pesquisadores e fãs do esporte.

---

## 📋 Visão Geral

Você já se perguntou:

- Quem foram, de fato, os grandes campeões do Jiu-Jitsu nas últimas décadas?
- Como comparar gerações e trajetórias usando métricas quantitativas, e não só títulos?
- O que diferencia a elite dos competidores intermediários e iniciantes?

Neste projeto, buscamos responder essas perguntas com:

- Coleta automatizada do histórico de lutas de centenas de atletas no BJJ Heroes.
- Construção e cálculo do ELO Rating para cada atleta ao longo do tempo.
- Agrupamento dos lutadores em clusters, revelando diferentes perfis de performance e evolução.
- Visualização gráfica interativa da trajetória dos maiores nomes e análise estatística detalhada.

---

## 🚀 Funcionalidades

- **Web scraping do BJJ Heroes:** Extração estruturada do histórico de lutas, resultados e informações de atletas.
- **Cálculo do ELO Rating:** Atualização dinâmica do rating após cada combate, simulando o progresso real do atleta.
- **Análise comparativa de trajetórias:** Gráficos de evolução, pico de ELO, queda de desempenho e rivalidades históricas.
- **Clusterização de atletas:** Identificação de grupos por performance (elite, intermediário, iniciante).
- **Painéis e dashboards:** Visualização dos dados, rankings e estatísticas competitivas.

---

## 🔧 Tecnologias Utilizadas

- **Python**
- **pandas**
- **NumPy**
- **requests**
- **BeautifulSoup**
- **matplotlib**
- **seaborn**
- **scikit-learn** (para agrupamentos)
- **Google Colab/Jupyter Notebook**

---

## 📂 Estrutura do Projeto

```plaintext
DADOS/                        # Dados finais tratados e prontos para análise, porém também incluí os dados brutos
RELATORIO_RASCUNHO/           # Rascunhos e o Relatório com os resultados.
README.md                     # Este arquivo com descrição e documentação do projeto
