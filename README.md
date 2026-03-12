# 💧 Integrando Biodiversidade Aquática e Segurança Hídrica no Estado do Rio de Janeiro

> Monografia de conclusão de curso — Bacharelado em Ciências Biológicas  
> Universidade do Estado do Rio de Janeiro (UERJ) — 2025  


---

## 📌 Sobre o Projeto

Este trabalho investiga a relação espacial entre a **biodiversidade aquática** e a **qualidade hídrica** no Estado do Rio de Janeiro, integrando dados georreferenciados de ocorrência de espécies com o Índice de Qualidade da Água (IQA) dos principais mananciais fluminenses.

A hipótese central é que áreas de maior riqueza de espécies aquáticas coincidem com condições favoráveis de qualidade da água — e que essa relação, quando mapeada, pode orientar estratégias de conservação e segurança hídrica no estado.

---

## 🎯 Objetivos

- Mapear a distribuição espacial da biodiversidade aquática fluminense (macroinvertebrados e peixes)
- Produzir mapas temáticos e analíticos das ocorrências por Região Hidrográfica (RH)
- Caracterizar espacialmente a qualidade hídrica a partir dos valores de IQA (2016–2024)
- Analisar a relação entre biodiversidade e qualidade da água nas 9 Regiões Hidrográficas do estado

---

## 🗺️ Área de Estudo

**Estado do Rio de Janeiro**, organizado em 9 Regiões Hidrográficas:

| RH | Nome |
|----|------|
| I | Baía da Ilha Grande |
| II | Baía de Guanabara |
| III | Médio Paraíba do Sul |
| IV | Piabanha |
| V | Guandu |
| VI | Dois Rios |
| VII | Lagos São João |
| VIII | Macaé e das Ostras |
| IX | Itabapoana |

---

## 🔬 Metodologia

### Dados de Biodiversidade
- Levantamento de dados secundários nas plataformas **GBIF**, **SiBBr** e **ICMBio**
- Grupos analisados: **insetos aquáticos** (Trichoptera, Ephemeroptera, Plecoptera, Odonata, Diptera, Hemiptera) e **peixes dulcícolas**
- Total de **8.970 registros de ocorrência** após limpeza e tratamento dos dados

### Dados de Qualidade Hídrica
- Série temporal de IQA de **2016 a 2024** fornecida pelo Programa de Saneamento Ambiental (PSAM/RJ)
- **4.251 pontos de monitoramento** distribuídos pelo estado

### Análise Espacial
Processamento realizado no **ArcGIS Pro** com as seguintes técnicas:

| Técnica | Aplicação |
|---------|-----------|
| Mapa de calor (Kernel Density) | Identificação de hotspots de biodiversidade |
| Interpolação por Krigagem | Superfície contínua de qualidade hídrica (IQA) |
| Análise de interseção | Relação entre ocorrências e Unidades de Conservação |
| Regressão linear por RH | Correlação estatística entre IQA e biodiversidade |

---

## 🗂️ Estrutura do Repositório

```
📁 dados/
   ├── ocorrencias_biodiversidade.csv   # Registros de ocorrência (8.970 pontos)
   └── iqa_mananciais_2016_2024.csv     # Índice de Qualidade Hídrica
📁 mapas/
   ├── fig1_regioes_hidrograficas.jpg
   ├── fig2_macroinvertebrados_RH.jpg
   ├── fig3_peixes_dulcicolas.jpg
   ├── fig4_densidade_biodiversidade.jpg
   ├── fig5_unidades_conservacao.png
   ├── fig6_iqa_tematico.jpg
   └── fig7_krigagem_iqa_biodiversidade.png
📁 tabelas/
   └── tabela_especies_por_RH.png
📄 README.md
📄 monografia_vitoria_carvalho_2025.pdf
```

---

## 📊 Principais Resultados

- **48% dos registros de biodiversidade** estão dentro de Unidades de Conservação, evidenciando o papel crucial das áreas protegidas
- A **RH Baía de Guanabara** concentra o maior número de registros, porém apresenta o **pior IQA médio (31,5)** — qualidade "ruim"
- As RHs de **Ilha Grande** e **Macaé** apresentam os melhores índices de qualidade hídrica (IQA 68,1 e 65,8)
- A relação entre IQA e biodiversidade é **heterogênea entre as RHs**, com correlações variando de negativa fraca a positiva moderada (R² até 0,41 em Lagos de São João)
- O grupo **EPT** (Ephemeroptera, Plecoptera e Trichoptera) mostrou-se um forte bioindicador, com maior diversidade nas RHs de melhor qualidade hídrica

---

## 🗺️ Mapas
**Regiões Hidrograficas do Estado do Rio de Janeiro** 
![RH] 
**Distribuição de macroinvertebrados aquáticos por RH**  
![Macroinvertebrados](mapas/fig2_macroinvertebrados_RH.jpg)

**Densidade de ocorrências da biodiversidade aquática**  
![Densidade](mapas/fig4_densidade_biodiversidade.jpg)

**Integração entre IQA (Krigagem) e Biodiversidade Aquática**  
![Krigagem IQA](mapas/fig7_krigagem_iqa_biodiversidade.png)

---

## 🛠️ Ferramentas Utilizadas

![ArcGIS Pro](https://img.shields.io/badge/ArcGIS%20Pro-0079C1?style=flat&logo=esri&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![GBIF](https://img.shields.io/badge/GBIF-4CAF50?style=flat&logoColor=white)
![SiBBr](https://img.shields.io/badge/SiBBr-2E7D32?style=flat&logoColor=white)

- **ArcGIS Pro** — análise espacial, mapas temáticos, krigagem e densidade de pontos
- **Excel** — organização, limpeza e tratamento dos dados tabulares
- **GBIF / SiBBr / ICMBio** — plataformas de dados de biodiversidade

---

## 👩‍🎓 Autora

**Vitoria Barbosa Barcellos de Carvalho**  
Bacharel em Ciências Biológicas — UERJ  
Instituto de Biologia Roberto Alcântara Gomes

**Orientadora:** Profa. Dra. Aliny P. F. Pires  
**Coorientadora:** MSc. Stephanie Vaz

---

## 📄 Citação

```
CARVALHO, Vitoria Barbosa Barcellos de. Integrando Biodiversidade Aquática e 
Segurança Hídrica no Estado do Rio de Janeiro. 2025. Monografia (Bacharelado em 
Ciências Biológicas) — Instituto de Biologia Roberto Alcântara Gomes, 
Universidade do Estado do Rio de Janeiro, Rio de Janeiro, 2025.
```

---

*Trabalho desenvolvido no Laboratório de Ecologia e Conservação de Ecossistemas — UERJ*
