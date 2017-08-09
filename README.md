# AngioScore
R package which allowed to query angiogenesis relations in Pubmed for a gene list

- 1/Load a gene list column for exemple set$gene to query relations in Pubmed between these genes and angiogenesis function
- 2/Compute an angioscore 
- 3/plot the results of Angiogenesis Citations and Angioscores as a scatterplot

USAGE:
- attach(set)
- data<-query(set$gene)
- final<-AngioScore(data)
- angioplot(final)

dependencies: 
- functions of utilities to query Pubmed and to parse XML files were adapted from the package OncoScore (Rocco P,2017)

References:
- Rocco P, Daniele R, Roberta S, Alessandra P, Luca S, Pierangelo F, Vera M,
Nicoletta C, Nitesh S, Carlo GP. OncoScore: a novel, Internet-based tool to
assess the oncogenic potential of genes. Sci Rep. 2017 Apr 7;7:46290. doi:
10.1038/srep46290. PubMed PMID: 28387367; PubMed Central PMCID: PMC5384236.

