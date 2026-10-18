+++
title="Pesquisa A"
description="teste"
template="research-page.html"
path="research/pesquisa-a"

[extra]
# Membros e coordenadores
members = ["joao-souza", "maria-silva"]
coordinators = ["maria-silva"]

# Status e infos básicas
status="Em andamento"
area = "Nome da área"
period = "2025-2027"
funding = "CNPq / FAPERJ"

# link
slug="pesquisa-a"

# resumo
abstract="Parágrafo de apresentação da pesquisa: qual é o tema, qual problema ela busca resolver e por que ele é relevante. Escreva de forma que alguém de fora do grupo consiga entender."

# Lista de publicações
publications = [
  "SILVA, M.; SOUZA, J. Título do artigo. *Nome do periódico ou evento*, 2026. [DOI](https://doi.org/)",
  "SOUZA, J. Título do trabalho. *Nome do evento*, 2025."
]

# Lista de links/materiais
links = [
  { texto = "Repositório", url = "https://github.com/" },
  { texto = "Dados", url = "https://example.com/dados" },
  { texto = "Relatório", url = "https://example.com/relatorio.pdf" }
]

# Texto de parceiros e apoio
partners = "Liste instituições parceiras e agências de fomento que apoiam a pesquisa."
+++

{% if lang == "en" %}
Here goes the main body content written in English...
{% else %}
## Objetivos

**Objetivo geral:** descreva em uma frase o propósito principal da pesquisa.

**Objetivos específicos:**

- Primeiro objetivo específico
- Segundo objetivo específico
- Terceiro objetivo específico

## Metodologia

Explique brevemente como a pesquisa é conduzida: etapas, técnicas, ferramentas e dados utilizados.

## Resultados parciais

- **2026:** descreva um resultado ou marco já alcançado.
- **2025:** descreva outro resultado ou marco.
{% endif %}
