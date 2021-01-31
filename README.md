# RNA-Protein

RNA Binding Proteins, (abbreviated as RBPs), are proteins which bind to RNA to form ribonucleoprotein complex. RBPs are vitally important in different pathways as they actively control mechanisms such as translation, RNA splicing, and RNA export. By regulating these mechanisms, RBPs modulate gene expressions.

Our pipeline mainly focuses on detecting RBP involvement in cancer pro- gression. The pipeline takes in the gene name of a user-chosen RBP, down- loads the raw reads from ENCODE, processes the reads, and determines the RBP’s potential roles in cancer progression. Users can specify our pipeline to be either default, differential expression analysis, or cancer analysis modes.

• Default Mode: The default mode includes steps of preprocessing, reads mapping, and peak calling. The output is a BED file which indicates all possible crosslink sites.

• Differential Expression Analysis Mode : This mode preforms differential expression (DE) analysis with the RBP gene knockdown datasets to hypothesis genes regulated by the user-specified RBP.

• Cancer Analysis Mode: The cancer analysis mode uses gene lists from both the previous modes to look at the role of these genes in both user provided gene expression input data, and also TCGA cancer gene expression data.
