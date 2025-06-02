# 🥋 Análise e Clusterização de Atletas de Jiu-Jitsu por ELO Rating

## 📊 Ranking Competitivo e Dinâmica do Alto Rendimento no Jiu-Jitsu

Este projeto foi desenvolvido como uma pipeline completa de análise de dados esportivos, integrando as etapas de extração, tratamento e organização de grandes volumes de informações históricas sobre lutas e atletas de Jiu-Jitsu. O histórico de combates foi coletado via web scraping automatizado diretamente do BJJ Heroes, garantindo uma base atualizada e confiável.

A etapa de processamento dos dados envolveu a limpeza, normalização e construção de variáveis fundamentais, como ELO Rating, taxa de vitória, número de finalizações e cluster competitivo. As análises exploratórias e visualizações interativas foram desenvolvidas utilizando Python, pandas, matplotlib e seaborn, facilitando a compreensão da evolução dos principais atletas, bem como o mapeamento de diferentes perfis competitivos ao longo das gerações.

O projeto possibilita não só identificar os grandes campeões do esporte de forma objetiva e quantitativa, mas também analisar rivalidades históricas, padrões de progressão e o impacto de diferentes estilos de carreira. Essa abordagem moderna e escalável transforma dados brutos em conhecimento estratégico para atletas, treinadores, estudiosos e fãs do Jiu-Jitsu.

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
DADOS/                        # Dados finais tr
atados e prontos para análise, porém também incluí os dados brutos
RELATORIO_RASCUNHO/           # Rascunhos e o Relatório com os resultados.
README.md                     # Este arquivo com descrição e documentação do projeto
