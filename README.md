# COEX-seq: COnvert a variety of measurements of gene EXpression in RNA-seq

COEX-seq is a web application(Shiny; a web application framework for R) framework for Convert a variety of measurements of gene expression in RNA-seq experiments. 


# INSTALL & RUN

1. Install R (www.r-project.org) & Rstudio (https://www.rstudio.com/)
2. Install Shiny package (https://cran.r-project.org/web/packages/shiny/index.html)
  - command line  
  - > install.packages("shiny") 
3. Download R codes [COEX-Seq](https://https://github.com/NIHxAI/COEX-Seq/tree/main/Data/COEX-seq.zip)
  - Unzip COEX-seq.zip
  - load server.r and ui.r
4. Download Reference Dataset 
  - Ensemble_length.txt [Ensemble_length](https://github.com/NIHxAI/COEX-Seq/Data/Ensemble_length.txt) 
  - Entrez_length.txt [Entrez_length](https://github.com/NIHxAI/COEX-Seq/Data/Entrez_length.txt)
  - GenBank_length.txt [GenBank_length](https://github.com/NIHxAI/COEX-Seq/Data/GenBank_length.txt)
  - GeneSymbol_length.txt [GeneSymbol_length](https://github.com/NIHxAI/COEX-Seq/Data/GeneSymbol_length.txt)
5. Run server.r(or ui.r) using Rstudio
6. Select Before Measurement : ex) Count
7. Select After Measurement : ex) TPM
8. Load Input file : ex) example file [Example_file_](https://github.com/NIHxAI/COEX-Seq/Data/RNAseq_readcount.txt)
9. Click: Header, Seperator
10. Click Submit




