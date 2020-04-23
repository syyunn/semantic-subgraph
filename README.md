# Semantic-subgraph
General notion about generating subgraph upon semantic query

## Usages
find T: (G, Q) -> G' where |G'| < |G| for a given semantic query Q such that SIM(Q, EMBED(G')) >> SIM(Q, EMBED(RANDOM(G')))

*RANDOM := Random Graph sampling 
* EMBED := any selcted Graph Embedding Algorithm
*SIM := Similarity Measure between Semantic and Graph-Embedding

## Methodology
Prepare latent space that generates subgraph when decoded. This will let the users to easily configure which subgraph of entire graph is required to be attended upon users' own semantic query/questions.

## Direct literatures
Mining integrated semantic networks for drug repositioning opportunities
semantic subgraphs for drug interaction analysis
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4736989/

## Related
### Disentangled Latent Approach
### GraphVAE

