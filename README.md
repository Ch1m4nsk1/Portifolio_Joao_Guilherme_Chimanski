# IPCA & Preço da Saca de Soja 60kg — Portfólio de Ciência de Dados

**Autor:** João Guilherme Chimanski de Souza \
**Contato:** joao99chimanski@hotmail.com \
**LinkedIn:** www.linkedin.com/in/joão-chimanski | **GitHub:** https://github.com/Ch1m4nsk1

## Sobre o projeto
Análise integrada entre o **IPCA (índice nacional de inflação)** e o **preço da saca de soja (CEPEA, Porto de Paranaguá)**. O objetivo é entender a volatilidade da soja ao longo do tempo e como a inflação influencia variabilidade dos preços agrícolas. Além de contribuir com a construção de um portifólio.

## Dados
- `data/raw/ipca_raw.csv` — IPCA mensal.                                        Fonte: IBGE
- `data/raw/cepea_raw.csv` — Preço diário/á vista da saca de soja (R$ e US$).   Fonte: https://www.cepea.org.br/br/indicador/soja.aspx

## Principais análises/extras


## Como rodar
```bash
git clone https://github.com/Ch1m4nsk1/Portifolio_Joao_Guilherme_Chimanski.git
cd Portifolio_Joao_Guilherme_Chimanski
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
