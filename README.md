

# Tendências Globais de Adoção de IA (2017–2025)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Data Formats](https://img.shields.io/badge/Format-XLSX%20%7C%20CSV-blue.svg)](#arquitetura-do-conjunto-de-dados)
[![Python](https://img.shields.io/badge/Python-Pandas-yellow.svg)](#ferramentas-recomendadas)
[![R](https://img.shields.io/badge/R-Tidyverse-blue.svg)](#ferramentas-recomendadas)

Compêndio de dados quantitativos e longitudinais sobre a evolução, adoção e impacto da Inteligência Artificial no cenário global entre 2017 e 2025.

---

## 📌 Visão Geral e Propósito

Este repositório reúne um conjunto de dados estruturado e padronizado destinado a sintetizar os principais indicadores globais de adoção e crescimento da Inteligência Artificial (IA) no período de **2017 a 2025**. 

O objetivo central é capturar a transição histórica desde a implementação inicial de modelos de *Machine Learning* tradicionais até a rápida consolidação da **IA Generativa**. O repositório foi desenvolvido especificamente para **pesquisadores, analistas de dados, economistas e formuladores de políticas públicas**, fornecendo uma base empírica e quantitativa rigorosa para subsidiar:

* **Estudos de Impacto Laboral e Econômico**: Avaliação das transformações nas rotinas de trabalho e funções corporativas.
* **Diagnósticos de *AI Readiness***: Avaliações de prontidão digital para governos e organizações.
* **Políticas Públicas de Tecnologia**: Formulação de estratégias regulatórias e de fomento baseadas em evidências.

---

## 📊 Dimensões Analíticas Cobertas

O conjunto de dados abrange **sete dimensões fundamentais**:

| # | Dimensão | Descrição e Escopo |
|---|---|---|
| **1** | **Adoção Organizacional** | Taxas globais de adoção e maturidade tecnológica em empresas ao longo do tempo. |
| **2** | **Funções de Negócios** | Mapeamento da implantação da IA em departamentos (P&D, Marketing, Operações, HR, etc.). |
| **3** | **Marcos de Usuários** | Volume, alcance e engajamento em ferramentas de IA (ex: OpenAI, GitHub Copilot). |
| **4** | **Investimento Privado** | Volume de capital de risco e investimentos corporativos discriminados por país. |
| **5** | **Setores Industriais** | Nível de penetração e taxa de utilização por indústrias e segmentos econômicos. |
| **6** | **Sentimento Público** | Índices de percepção humana, confiança, ansiedade e aceitação social da automação. |
| **7** | **KPIs Globais** | Indicadores chave de desempenho, produtividade e retorno sobre investimento (ROI). |

---

## 🔬 Metodologia e Rigor Científico

A compilação dos dados segue um pipeline rigoroso de **5 etapas**:
1. **Identificar**: Seleção criteriosa de fontes primárias com autoridade institucional reconhecida.
2. **Extrair**: Coleta direta de métricas quantitativas (porcentagens, usuários, valores em USD, escores).
3. **Verificar e Classificar**: Validação de cada métrica e atribuição de um nível de confiabilidade na coluna `Data_Type`.
4. **Estruturar**: Mapeamento tabular normalizado com citações diretas em nível de linha (*row-level attribution*).
5. **Preparar**: Exportação limpa e interoperável para os formatos `.xlsx` e `.csv`.

### Níveis de Confiabilidade (`Data_Type`)

* **`Verificado`**: Dados extraídos diretamente de publicações primárias oficiais.
* **`Modelado/Ancorado`**: Dados interpolados ou extrapolados a partir de ancoragens verificadas com metodologia documentada.
* **`Projetado`**: Estimativas prospectivas baseadas em trajetórias históricas confirmadas.

---

## 🏛️ Fontes Primárias e Institucionais

Os dados consolidados neste repositório provêm das seguintes organizações de referência:

* **McKinsey & Company**: Pesquisas globais sobre estado da IA e adoção corporativa.
* **Stanford HAI (*Artificial Intelligence Index Report*)**: Métricas de P&D, capacidade técnica e investimentos.
* **World Bank**: Indicadores socioeconômicos e prontidão em economias emergentes.
* **IBM**: Índices de adoção em empresas e barreiras tecnológicas globais.
* **Oxford Insights**: Índice de prontidão dos governos para a IA (*Government AI Readiness Index*).
* **ITU / GSMA**: Estatísticas globais de conectividade e infraestrutura de telecomunicações.
* **SimilarWeb**: Tráfego web, retenção de usuários e métricas de plataformas online.
* **OpenAI & GitHub/Microsoft**: Divulgações de métricas de adoção de IA Generativa e plataformas de código.

---

## 📁 Estrutura do Repositório

```bash
.
├── README.md                   # Documentação principal do repositório
├── LICENSE                     # Licença de uso (CC BY 4.0)
├── data/                       # Arquivos de dados brutos e processados
│   ├── ai_adoption_2017_2025.xlsx  # Pasta de trabalho formatada (Multitabs)
│   ├── csv/                    # Arquivos CSV para processamento programático
│   │   ├── organizational_adoption.csv
│   │   ├── business_functions.csv
│   │   ├── user_milestones.csv
│   │   ├── private_investment.csv
│   │   ├── industry_sectors.csv
│   │   ├── public_sentiment.csv
│   │   └── key_kpis.csv
└── docs/                       # Dicionário de dados e notas metodológicas
    └── data_dictionary.md
