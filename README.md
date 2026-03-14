# From Geography to Development

JSC370 Midterm Project — Zekun Song, March 2026

Cross-country observational analysis (2019) examining how geographic characteristics relate to economic structure, and how structure relates to national income.

## Files

- `midterm_project.qmd` — Quarto source
- `midterm_project.html` — Rendered report

## Data

- [REST Countries API](https://restcountries.com/) — geographic metadata
- [World Bank Development Indicators](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392) — GDP per capita, agriculture share, trade share, urbanisation

## Reproduce

```bash
pip install requests pandas numpy matplotlib scipy statsmodels plotnine folium
quarto render midterm_project.qmd
```
