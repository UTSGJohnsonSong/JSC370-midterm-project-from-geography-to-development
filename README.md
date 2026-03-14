# From Geography to Development

JSC370 Midterm Project
Zekun Song

A cross-country observational analysis examining how geographic characteristics relate to economic structure, and how economic structure in turn relates to national income (2019 year data).

---

## Research Question

> To what extent is geography associated with economic development across countries, and does this relationship partly operate through differences in economic structure?

**Subquestions:**

1. Are geographic characteristics associated with economic structure across countries?
2. Are economic structure variables associated with national income levels?
3. Does the association between geography and income weaken after controlling for economic structure?

---

## Report Sections

| Section | Description |
|---|---|
| **Introduction** | Background, motivation, conceptual framework, and research questions |
| **Methods** | Data acquisition (APIs), cleaning, wrangling, and analytical tools |
| **Preliminary Results** | Summary statistics, publication-quality figures, regression tables |
| **Summary** | Key findings and plan for final project (ML modeling, interactive visualizations, website) |

---

## Files

| File | Description |
|---|---|
| `midterm_project.qmd` | Main Quarto source file |
| `midterm_project.html` | Rendered HTML report |

---

## Data Sources

| Source | Access Method | Variables |
|---|---|---|
| [REST Countries API](https://restcountries.com/) | HTTP API | Region, landlocked status, area, borders |
| [World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392) | `wbgapi` Python package | GDP per capita, agriculture share, trade share, urbanisation |

---

## Reproducibility

Install the required Python packages, then render the Quarto file:

```bash
pip install requests pandas numpy matplotlib seaborn scipy statsmodels wbgapi
quarto render notebook.qmd