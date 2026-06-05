# Aula 08 — Pipeline ETL

Construção de um pipeline ETL modular em Python.

---

## Arquitetura

| Arquivo | Responsabilidade |
|---|---|
| `etl.py` | Extract: lê e concatena os arquivos de dados |
| `pipeline.py` | Orquestra o pipeline, chamando as etapas em sequência |
| `dados/` | Pasta com os arquivos de entrada |

---

## Fluxo

1. **Extract** — lê e concatena os arquivos da pasta `dados/`
2. **Transform** — transforma os arquivos conforme regras de negócio
3. **Load** — carrega os dados processados (2 caminhos possíveis)

---

##  Dependências

Gerenciadas via Poetry (`pyproject.toml`).

---

##  Dados

Os arquivos `.csv` e `.parquet` utilizados no pipeline foram criados conforme sugerido no código do `etl.py` e executados via `pipeline.py`.

