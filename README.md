The snRNA-seq analysis Rmd file describes single-nuclei RNA-seq analysis performed in the article entitled [Autism-related gene intergenerationally regulates neurodevelopment and behavior in fish through non-genetic mechanisms](https://www.researchsquare.com/article/rs-2617834/v1).

We compare here two pools of ~50 medaka (*Oryzias latipes*) embryos at the late neurula stage (stage 18) called MCH+/HMC and MCH-/HPC. Embryos of both pools are mutant for the gene *auts2a* at the heterozygous state. 
* MCH+/HMC embryos originate from a wild-type mother and a homozygous *auts2a* mutant father. The wild-type *auts2a* allele of MCH+/HMC embryos was provided by the mother (*i.e.,* the mutant *auts2a* allele being provided by the father).
* In the contrary, MCH-/HPc embryos originate from a wild-type father and a homozygous *auts2a* mutant mother. The wild-type *auts2a* allele of MCH-/HPC embryos was provided by the father (*i.e.,* the mutant *auts2a* allele being provided by the mother).

The analysis was performed based on the [publicly available Seurat tutorials](https://satijalab.org/seurat/articles/get_started.html).

Before processing the analysis, the two following directories shoud be created :

The **"./data_mdk/input/"** directory that contains :
* Cellbender output folders
* The list of medaka mitochondrial gene names called "medaka-mito-genenames.csv" obtained following the procedure described in [10X Genomics Support](https://support.10xgenomics.com/single-cell-gene-expression/software/visualization/latest/tutorial-reclustering#header).
* The supplementary excel file called "aar4362_tables2.xlsx" from [Wagner et al., 2018](https://pubmed.ncbi.nlm.nih.gov/29700229/).

The **"./data_mdk/output/"** diectory that will contain output from this analysis.
