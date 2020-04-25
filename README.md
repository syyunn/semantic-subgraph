# Semantic-subgraph
General notion about generating subgraph upon semantic query

## Edge-semantics
Comprised of 1) direction 2)semantic-label

## Usages
Find T: (G, Q) -> G' where |G'| < |G| for a given semantic query Q such that SIM(Q, EMBED(G')) >> SIM(Q, EMBED(RANDOM(G')))

*RANDOM := Random Graph sampling 

*EMBED := any selcted Graph Embedding Algorithm

*SIM := Similarity Measure between Semantic and Graph-Embedding

## Methodology
Prepare latent space that generates subgraph when decoded. This will let the users to easily configure which subgraph of entire graph is required to be attended upon users' own semantic query/questions.

## Direct literatures
Mining integrated semantic networks for drug repositioning opportunities
semantic subgraphs for drug interaction analysis
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4736989/pdf/peerj-04-1558.pdf

https://arxiv.org/pdf/1910.08288.pdf

https://pdfs.semanticscholar.org/f947/5f2ef3c186e17be45fa7ea7ca1c7537bb1ae.pdf

http://web.stanford.edu/class/cs341/project/Zhang-Yang-Lou_report.pdf

## Motifs
https://cs.stanford.edu/people/jure/pubs/motifs-wsdm17.pdf

## Related
### Disentangled Latent Approach
### GraphVAE

