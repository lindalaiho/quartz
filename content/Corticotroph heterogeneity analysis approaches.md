### 1) Predefine subcluster borders and see if they correspond

### 2) Try and project cells from a subcluster to another dataset subcluster
scmap [Kiselev 2018](https://doi.org/10.1038/nmeth.4644)
- Essentially, the goal is "the assignment of each new cell into a known cell type or novel cluster"
- "The simplest existing approach (e.g. scmapCell) is to analyse each cell to be annotated independently. For each new cell, its most similar cells in the atlas are found and a consensus rule on their annotations can be used to guess the type of the new cell too. This design is straightforward but unable to find novel clusters, since new cells are never compared to one another." then again scmapCluster will "assign new cells to a known type or reject them into an “unknown” bin [source](https://www.nature.com/articles/s41598-020-71805-1) 
