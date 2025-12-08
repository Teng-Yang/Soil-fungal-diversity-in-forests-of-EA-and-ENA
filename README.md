Supporting R code for Manuscript: "Environmental heterogeneity shapes higher soil fungal diversity in forests of eastern Asia compared to eastern North America"

This repository contains three R scripts that support the analyses presented in Yang et al.'s manuscript titled "Environmental heterogeneity shapes higher soil fungal diversity in forests of eastern Asia compared to eastern North America". These scripts cover data processing, construction of plant phylogenetic trees, and testification of three hypotheses.

Repoitroy Contents
1. H1 code.r
   1.1. Purpose: Testification of H1 - Soil fungal diversity in EA is significantly greater than that in ENA
   1.2. Key Functions: i) Creat the boxplots showing significantly higher fungal diversity in EA than ENA based on five datasets; ii) Creat the merged figures showing fungal diversity comparison between EA and ENA across the disjunct plant phylogenetic tree; iii) Creat the boxplots showing significant difference in fungal diversity among plant genera. All the above figures are attached with statistical results.
2. H2-H3 code.r
   2.1 Purpose: Testification of H2 - Fungal diversity increases significantly with plant diversity, and H3 - Fungal diversity is primarily controlled by environmental rather than plant factors, with greater climatic and topographic heterogeneity promoting greater diversity in EA forests
   2.2. Key Functions: i) Perform the OLS multiple regression models disentangling the drivers of soil fungal alpha diversity across EA and ENA; ii) summary of multiple OLS regression models by donut diagrams; iii) Create partial regression plots to illustrate the effects of key environmental predictors on soil fungal diversity across EA and ENA forests
3. Plant phylogenetic tree construction.r
   3.1. Purpose: Draw the plant phylogenetic trees to show the study design for the study
   3.2. Key Functions:  i) draw phylogenetic tree for complete datasets; ii) draw phylogenetic tree for disjunct datasets 
