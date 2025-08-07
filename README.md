# Mining inside Indigenous Lands

[Visit the website](https://phillctw.github.io/mining_indigenous_lands/)

In this project, I set out to uncover how individuals and companies use legal processes to pursue mining inside Indigenous lands—or at the very least, to exert pressure on these protected areas and challenge the boundaries of protection. 

## Findings

The investigation uncovered a significant number of mining processes overlapping Indigenous lands, with a notable concentration of activity emerging since 2010.

## Data Collection

All data used in this project was sourced from:
- [SIGMINE](https://dados.gov.br/dados/conjuntos-dados/sistema-de-informacoes-geograficas-da-mineracao-sigmine) - Sistema de Informações Geográficas da Mineração (Mining Geographic Information System)
- [Funai](https://www.gov.br/funai/pt-br/atuacao/terras-indigenas/geoprocessamento-e-mapas) - Fundação Nacional dos Povos Indígenas (National Indigenous Foundation)

## Data Analysis

This project relied on a combination of tools for geospatial analysis, data processing, visualization, and web development:

- **QGIS** was used to cross-reference official Indigenous land boundaries with registered mining coordinates and to generate base maps.
- `Pandas` library handled the analysis of cross-referenced datasets exported from QGIS
- **Datawrapper** was used to design a static graph illustrating key trends
- **Illustrator** refined both the QGIS-generated maps and the Datawrapper chart
- **HTML and CSS** formed the structure and styling of the website
- **ai2html** to build the scrollytelling map
- **D3** was used for the scroll-based storytelling and enabled the interactive chart
- **Gemini** assisted in developing the logic for the D3 interactions

## Learning

A significant portion of this project was dedicated to working with data in QGIS, followed by extensive refinement in Illustrator. As a result, I became more confident in handling geospatial data and deepened my understanding of Illustrator’s workflow, identifying blind spots and improving my overall proficiency with the tool.

I also consolidated my knowledge of the `Pandas` library and had the opportunity to apply regular expressions (regex) to perform targeted data cleaning tasks.

I had the chance to experiment a bit with D3.js (with support from Gemini), a tool I had been interested in exploring further.

Finally, I spent a considerable amount of time developing the website, which helped me solidify my understanding of HTML, CSS and ai2html. Initially, I built the entire site without ai2html, using a simpler scrollama setup with static images. However, visualization issues on the mobile version led me to switch to ai2html for better responsiveness.

## To look forward

One of my initial goals was to calculate the area of Indigenous lands overlapped by mining processes. While I managed to produce some preliminary results, time constraints prevented me from developing effective visualizations, so this analysis was not included in the final project.

Another future direction would be to incorporate satellite imagery to visualize where mining activities intersect Indigenous lands. This approach could reveal whether those areas are already impacted and open new storytelling possibilities.