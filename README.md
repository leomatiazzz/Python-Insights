# 📊 Projeto de Análise de Dados

Este projeto analisa o banco de dados `cancelamentos.csv` usando Python e Jupyter/Colab.

---

## 🚀 Acesse no Google Colab

🔗 **Execute diretamente no navegador:**  
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14CCEjqAJVmcXwyx15dyBKLX_C-AKEewx?authuser=1#scrollTo=xW5YwobnyAqa)

> ⚠️ Observação: você precisa ter os dados no seu Google Drive (link incluído abaixo).

---

## 💻 Executar localmente

Você também pode:
- Baixar o notebook `inicial.ipynb`
- Abrir no VSCode (com a extensão Jupyter)
- Usar a base de dados completa (`cancelamentos.csv`) ou a versão reduzida (`cancelamentos_sample.csv`), disponível no repositório.

---

## 📁 Sobre os dados

- `cancelamentos.csv`: base de dados original e mais completa (**maior que 50MB**)
- `cancelamentos_sample.csv`: versão reduzida, útil para testes rápidos

Caso use o Google Colab, certifique-se de montar seu Google Drive e ajustar o caminho dos arquivos, por exemplo:

```python
from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df = pd.read_csv('/content/drive/MyDrive/sua-pasta/cancelamentos.csv')

