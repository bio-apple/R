## Common Methods for Installing R Packages
方法一:

    options(BioC_mirror="http://mirrors.ustc.edu.cn/bioc/")
    source("http://www.bioconductor.org/biocLite.R")
    biocLite("GDCRNATools")
    Rscript -e "BiocManager::install(\"ComplexHeatmap\")"

方法二：

    Rscript -e "install.packages(c(\"BiocManager\"))"

方法三：

    R CMD INSTALL EnrichmentBrowser_2.4.5_CA_edit.tar.gz

## Popular R Packages for Bioinformatics

**Olink**<br>
https://cran.r-project.org/web/packages/OlinkAnalyze/
<pre>install.packages("OlinkAnalyze")</pre>

**WGCNA**Weighted Gene Co-expression Network Analysis）<br>
https://cran.r-project.org/web/packages/WGCNA/index.html
<pre>BiocManager::install("WGCNA")</pre>

**sesame**SEnsible Step-wise Analysis of DNA MEthylation BeadChips<br>
https://bioconductor.org/packages/release/bioc/html/sesame.html
<pre>BiocManager::install("sesame")</pre>

**Seurat**R toolkit for single cell genomics<br>
https://satijalab.org/seurat/
<pre>install.packages('Seurat')</pre>

**DESeq2**Differential gene expression analysis based on the negative binomial distribution<br>
https://bioconductor.org/packages/release/bioc/html/DESeq2.html
<pre>BiocManager::install("DESeq2”)</pre>

**edgeR**Empirical Analysis of Digital Gene Expression Data in R<br>
https://bioconductor.org/packages/release/bioc/html/edgeR.html
<pre>BiocManager::install("edgeR")</pre>

**clusterProfile**A universal enrichment tool for interpreting omics data<br>
https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html
<pre>BiocManager::install(“clusterProfiler")</pre>

**vegan**COrdination methods, diversity analysis and other functions for community and vegetation ecologists<br>
https://cran.r-project.org/web/packages/vegan/index.html
<pre>BiocManager::install("vegan")</pre>

**devtools**Tools to Make Developing R Packages Easier<br>
https://cran.r-project.org/web/packages/devtools/index.html
<pre>install.packages("devtools")</pre>

**methylKit**DNA methylation analysis from high-throughput bisulfite sequencing results<br>
https://www.bioconductor.org/packages/devel/bioc/html/methylKit.html
<pre>BiocManager::install("methylKit")</pre>

**epialleleR**Fast, Epiallele-Aware Methylation Caller and Reporter<br>
https://www.bioconductor.org/packages/release/bioc/html/epialleleR.html
<pre>BiocManager::install("epialleleR")</pre>

