# analise-impacto-social-globais
Mapeamento da vulnerabilidade social e econômica nas regiões do Brasil ./ Mapping of social and economic vulnerability across Brazilian regions
## Objetivo

Criar uma análise visual e estatística da vulnerabilidade socioeconômica no Brasil, utilizando dados públicos para:

- Identificar regiões em maior risco social
- Propor estratégias de alocação de recursos
- Analisar correlações com renda, escolaridade, infraestrutura etc.

---

## Ferramentas utilizadas

- Python
- Pandas
- Matplotlib / Seaborn
- StatsModels
- Regressão simples e múltipla
- Funções automatizadas (plot, modelagem, etc.)

---
## ⚖️ Licença

Este projeto está sob licença MIT. Fique à vontade para usar, modificar e contribuir.

---

```bash
.
├── dataRaw/                  # Dados brutos (não tratados)
│   └── base_de_dados.csv
│
├── dataProcessed/           # Dados tratados e prontos pra análise
│   └── dados_tratados.csv
│
├── figures/                 # Gráficos gerados
│   └── grafico_renda.png
│
├── notebooks/               # Notebooks de análise
│   ├── 01_analise_exploratoria.ipynb
│   └── 02_regressao_multipla.ipynb
│
├── src/                     # Códigos Python organizados
│   ├── preprocessing.py
│   ├── regressao.py
│   └── visualizacao.py
│
├── LICENSE
├── README.md
└── requirements.txt

## 🚀 Rodando o projeto localmente

1. Clone o repositório:
```bash
git clone https://github.com/Santosteveialima/analise-impacto-social-globais.git


2. Acesse a pasta do projeto:
´´bash
cd analise-impacto-social-globais

3.instale as dependências:
´´´bash
pip install -r requirements.txt
4.Execute os notebooks na pasta notebooks ou scripts em src/
