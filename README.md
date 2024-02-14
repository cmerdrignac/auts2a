The snRNA-seq analysis Rmd file describes single-nuclei RNA-seq analysis performed in the article entitled [Autism-related gene intergenerationally regulates neurodevelopment and behavior in fish through non-genetic mechanisms](https://www.researchsquare.com/article/rs-2617834/v1).

The analysis was performed based on the [publicly available Seurat tutorials](https://satijalab.org/seurat/articles/get_started.html).

Before processing the analysis, the two following directories shoud be created :

The *"./data_mdk/input/"* directory that contains :
* Cellbender output folders
* The list of medaka mitochondrial gene names called "medaka-mito-genenames.csv" obtained following the procedure described in [10X Genomics Support](https://support.10xgenomics.com/single-cell-gene-expression/software/visualization/latest/tutorial-reclustering#header).
* The supplementary excel file called "aar4362_tables2.xlsx" from [Wagner et al., 2018](https://pubmed.ncbi.nlm.nih.gov/29700229/).

The *"./data_mdk/output/"* that will contain output from this analysis.
