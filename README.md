# Bibliometric Analysis of Small Lakes Research (1990–2024)

A bibliometric analysis of scientific literature on small lakes using 
data retrieved from the Scopus database. This project was originally 
conducted during an internship and has been fully rebuilt in R as a 
portfolio project.

---

## About the Project

Small lakes, often defined as water bodies with a surface area of less 
than one square kilometer, play a critical role in biodiversity, 
biogeochemical processes, and local livelihoods — yet they remain 
underexplored compared to larger lakes. This analysis maps the 
scientific landscape of small lakes research to identify key contributors, 
dominant themes, and gaps in the literature.

**Research objectives:**
- Evaluate the nature and evolution of small lakes research by identifying 
  key authors, journals, and countries
- Uncover the intellectual structure of the field through science mapping 
  and thematic analysis

---

## Dataset

- **Source:** Scopus database
- **Search term:** "small lake*"
- **Raw records:** 13,181 documents (1898–2025)
- **Cleaned records:** 11,391 documents (1990–2024)
- **Document types retained:** Articles and Reviews only

---

## Methods & Tools

| Tool | Purpose |
|---|---|
| R / RStudio | Primary analysis environment |
| `bibliometrix` | Bibliometric analysis and science mapping |
| `tidyverse` | Data cleaning and manipulation |
| `ggplot2` | Data visualization |
| `maps` | Country production world map |

---

## Repository Structure
```
├── bibliometric-analysis.Rmd   # Full R Markdown source code
├── index.html                  # Knitted HTML report (portfolio artifact)
├── 01_annual_production.png    # Annual scientific production chart
├── 02_top_authors.png          # Top 10 most productive authors
├── 03_top_journals.png         # Top 10 most relevant journals
├── 04_country_production.png   # Country scientific production map
├── 05_keywords.png             # Top 20 author keywords
├── 06_thematic_map.png         # Thematic map
└── 07_citation_analysis.png    # Top 10 most cited papers
```

---

## Key Findings

- **11,391 documents** published across **1,729 journals** by **28,700 authors**
- Annual growth rate of **3.53%** with peak output in **2022 (685 documents)**
- **USA, China, and Canada** are the most productive countries
- Leading journals: *Hydrobiologia* and *Journal of Paleolimnology*
- Dominant themes: **climate change, eutrophication, and paleolimnology**
- International co-authorship rate of **27.71%** reflects strong global collaboration
- A notable gap exists in **social and economic dimensions** of small lakes research

---

## Author

**Kate Regine B. Cunanan**
University of the Philippines Los Baños
[GitHub](https://github.com/krbcunanan)
