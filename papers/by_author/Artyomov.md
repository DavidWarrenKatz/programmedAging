# Maxim N. Artyomov

Maxim N. Artyomov is an immunologist recognized for his research on immune system aging, particularly the mechanisms of chronic inflammation and clonal expansion in aging immune cells.

---

## Key Publications

### 1. [**Comprehensive Profiling of an Aging Immune System Reveals Clonal GZMK+ CD8+ T Cells as Conserved Hallmark of Inflammaging**](https://www.sciencedirect.com/science/article/pii/S1074761320304921#:~:text=As%20a%20result%2C%20we%20comprehensively%20described%20the%20cellular,population%20that%20is%20conserved%20between%20the%20two%20species.)
**Denis Mogilenko et al. and Maxim N. Artyomov, Immunity, 2021**

**Summary**:  
The authors generated a multi-omics single cell dataset of the immune system and identified a new class of CD8+ T cells that emerges with aging in mice and men. This emergence was then confirmed in public (Kimmel at al. 2019) datasets as well as heterochronic transfer experiments. These aging-associated CD8+ clonal T cells (Taa) were characterized by their expression of Gzmk as well as their co-expression of the transcription factor TOX (exhaustion) and the checkpoint molecule PD-1. The emergence of this cell population with age could not be confirmed by flow cytometry, but was supported by other approaches. Gzmk was not detected in cells other than this subpopulation of T cells. 

**Identifying Gzmk Expressing CD8+ clonal T cells As Emerging With Aging**:  
![Figure3c](../../images/papers/Artyomov/Figure1BCD.png)  

scRNA was performed on approximately 35,000 cells from four tissues (spleen, peritoneom, lungs, liver) and two age-points (3-6 months and 17-24 months) in six male C57BL/6J mice. For each tissue, highly variable genes were selected and then dimensionality reduction was performed on variable genes to call cell-type clusters. Within each cluster, subclusters were called by measuring expression levels of a list of marker genes. For each subcluster, differential expression analysis for each of the two timepoints was performed. Gzmk+ CD8+ T cells were identifed as being significantly upregulated in old age mice in all four tissues by this analysis. 

**Validating Aging Associated Populations with Flow Cytometry**:  
![Figure3c](../../images/papers/Artyomov/Figure2A-G.png)  

Some of the age-association population changes could be confirmed by flow cytometry, such as the depletion of peritoneum macrophages. For example, in Figure 2A, flow cytometry on an independent cohort of mice was used to seperate macrophages and dendritic cells, and then a new round of scRNA-Seq was performed on the macrophages and dendritic cells. ICAM2 expression was specific to peritoneal macrophages and dendritic cells, and flow cytometry confirmed a significant decrease in ICAM2+ macrophages in the mouse peritoneum with age (Figure 2C). Contrary to the CD4+ T cells, the authors observed an increased clonality among aged CD8+ T cells that was concentrated within the CD8+ Taa cell clusters.  Remarkably, identical TCR clones were found simultaneously in different organs in aged, but not in young mice. The authors also showed that GZMK has the potential to exacerbate the SASP alone or in combination with IFNγ in mouse 3T3 fibroblasts.


**One Month In Old Body Results in Taa Phenotype**
![Figure5A](../../images/papers/Artyomov/Figure5A.PNG)  
Splenic CD8+ T cells were transfered from young mice into young or aged mice (Figure 5A). In aged mice, 1 month post transfer was sufficient to convert circulating donor CD8+ T cells into the TOX+PD-1+ phenotype to the same extent as host CD8+ T cells (Figures 5A–5C), increase expression of CD49d by these cells, and promote their accumulation into various organs (Figures 5D–5F, S5A, and S5B). The authors performed scRNA-seq analysis of donor and host splenic CD8+ T cells.

**One Month In Young Body Does Not Rejuvenate Taa Cells**
![Figure5GHI](../../images/papers/Artyomov/Figure5GHI.png)  
CD8+ T cells (including the TOX+PD-1+ cell population) were transfered from aged to young mice (Figure 5G). After one month, CD8+ Taa cells maintained the TOX+PD-1+ phenotype and preserved elevated levels of CD49d in a young environment (Figures 5G–5K). Moreover, 1 month in the young host was sufficient for TOX+PD-1+ CD8+ Taa cells from aged donors to infiltrate multiple organs (Figures S5H–S5J). The authors suggest this is evidence that differentiated CD8+ Taa cells have a stable phenotype that is linked to high capacity for homing into tissues.

**Commentary**:  
This research significantly advances our understanding of the immune components contributing to inflammaging, particularly the role of clonal expansions in CD8+ T cells. The identification of conserved markers like GZMK+ CD8+ T cells opens avenues for developing therapeutic strategies aimed at modulating immune function in aging populations. This work underscores the potential for rejuvenating immune responses by selectively targeting cells that drive chronic inflammation without affecting the broader immune functionality.

**Image**:  
*Caption*: Representative visualization of GZMK+ CD8+ T cells as a conserved marker of aging in human and mouse immune profiles, as presented in the study. The cells show characteristic markers that increase with age and contribute to a chronic inflammatory environment.
