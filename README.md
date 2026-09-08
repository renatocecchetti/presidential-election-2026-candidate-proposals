# Comparativo de Propostas — Presidência da República 2026

Tabela comparativa **navegável** das propostas registradas no TSE pelos seis candidatos à Presidência da República mais bem colocados no agrupamento de pesquisas da CNN (Eleições 2026), organizadas por eixo temático.

👉 **Página publicada (GitHub Pages):** https://renatocecchetti.github.io/presidential-election-2026-candidate-proposals/

## O que é

- Cada proposta é apresentada de forma **factual e neutra**, com a **fonte** indicada: a(s) página(s) do respectivo plano de governo (PDF).
- A página permite **filtrar por eixo temático, filtrar por candidato e buscar por palavra** dentro das propostas.
- **Sem qualquer juízo de valor**, análise de mérito ou verificação de viabilidade — material puramente descritivo.

## Candidatos (ordem do agrupamento de pesquisas da CNN)

| # | Candidato | Partido | Plano (PDF) |
|---|-----------|---------|-------------|
| 1 | Lula | PT | `lula-pt.pdf` |
| 2 | Flávio Bolsonaro | PL | `flavio-bolsonaro-pl.pdf` |
| 3 | Augusto Cury | Avante | `augusto-cury-avante.pdf` |
| 4 | Ronaldo Caiado | PSD | `ronaldo-caiado-psd.pdf` |
| 5 | Renan Santos | Missão | `renan-santos-missao.pdf` |
| 6 | Romeu Zema | Novo | `romeu-zema-novo.pdf` |

## Eixos temáticos

Economia e Responsabilidade Fiscal · Segurança Pública · Saúde · Educação · Trabalho e Emprego · Meio Ambiente e Energia · Agronegócio e Segurança Alimentar · Combate à Pobreza e Desenvolvimento Social · Infraestrutura e Saneamento · Política Externa e Soberania · Gestão Pública / Reforma do Estado / Instituições · Cultura, Esporte e Turismo

## Estrutura do repositório

- `index.html` — a página interativa (dados embutidos; funciona no GitHub Pages sem back-end).
- `data/*.json` — propostas estruturadas por candidato (proposta + páginas de origem).
- `extracted/*.txt` — texto integral extraído de cada PDF, com marcadores de página (base da análise).
- `*.pdf` — planos de governo originais protocolados no TSE.

## Metodologia

1. Extração do texto de cada PDF página a página.
2. Identificação das propostas concretas por eixo temático, com registro da(s) página(s) de origem.
3. Paráfrase neutra (sem juízo de valor) e publicação em tabela comparativa navegável.

As etiquetas de fonte em cada célula apontam para o PDF do plano na página correspondente (`arquivo.pdf#page=N`).
