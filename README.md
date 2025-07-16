<<<<<<< HEAD
# 📊 Análise de Tempo Médio Processual - TJGO

Este repositório apresenta uma análise independente do **tempo médio de tramitação dos processos baixados** no **Tribunal de Justiça do Estado de Goiás (TJGO)**, utilizando **Python e Pandas**.

O principal objetivo é **validar os dados oficiais divulgados pelo Sistema de Estatística e Transparência (SET)** do TJGO, promovendo a confiança pública nas iniciativas de **transparência do Poder Judiciário**.

---

## 📌 Objetivos

- Calcular o tempo médio de tramitação processual com base em dados brutos.
- Verificar se os números oficiais do TJGO são **replicáveis e confiáveis**.
- Aplicar um fluxo de análise baseado em **ETL (Extract, Transform, Load)** com foco em qualidade dos dados.

---

## ⚙️ Funcionalidades

- 📥 **Leitura de dados** a partir de arquivos `.csv`
- 🧹 **Limpeza e transformação**:
  - Conversão de colunas para `datetime`
  - Remoção de registros nulos ou inconsistentes
  - Cálculo de duração de processos em dias
- 📊 **Agregação por instância, entrância, comarca e serventia**
- 💾 **Exportação dos resultados** para novo arquivo `.csv`

---

## 🛠️ Metodologia

1. **Extração dos dados**
2. **Conversão e limpeza de colunas de datas**
3. **Cálculo do tempo de tramitação**
4. **Filtragem de inconsistências**
5. **Agrupamento e cálculo da média**
6. **Exportação dos resultados**

O processo prioriza integridade dos dados e exclusão de registros que possam distorcer as estatísticas.

---

## 🚀 Como Usar

### 📋 Pré-requisitos

- Python 3.9.13  
- Bibliotecas: `pandas`, `numpy`, `pathlib`

```bash
pip install pandas numpy pathlib
```

## 📂 Estrutura esperada
```bash
/seu_projeto/
├── uploads/
│   └── relatorio_processos.csv
├── tempomedio.ipynb  (ou seu_script.py)
├── README.md
```
---

## ▶️ Execução

1. **Clone o repositório ou organize as pastas conforme acima.**

2. **Coloque seu arquivo .csv dentro da pasta uploads/.**

3. **Execute o script Python ou notebook, apontando para o caminho correto:**

```python
 caminho_arquivo_entrada = 'uploads/seu_arquivo.csv'
```

4. **O resultado será salvo automaticamente em uma nova pasta: resultados_da_analise/.**

---

## 📈 Resultados

- A análise confirmou a precisão dos dados divulgados pelo SET/TJGO, validando de forma independente as estatísticas oficiais.

- Pequenas variações foram estatisticamente irrelevantes, reforçando a credibilidade do sistema de dados judiciais.



=======
>>>>>>> 28c1d6fc21bd8efbaee668ee60efffcddf3c6af0

