# Semantic-subgraph
General notion about generating subgraph upon semantic query

## Usages
find T: (G, Q) -> G' where |G'| < |G| for a given semantic query Q such that SIM(Q, EMBED(G')) >> SIM(Q, EMBED(RANDOM(G')))

*RANDOM means Random Graph sampling and EMBED means any selcted Graph Embedding Algorithm
*SIM means Similarity Measure between semantic and graph-embedding

## Methodology
Prepare latent space that generates subgraph when decoded. This will let the users to easily configure which subgraph of entire graph is required to be attended upon users' own semantic query/questions.

## Related
### Disentangled Latent Approach
### GraphVAE
