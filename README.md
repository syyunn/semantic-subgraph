# Semantic-subgraph
General notion about generating subgraph upon semantic query

## Usages
find T: G -> G' where |G'| < |G| for given Q where where Similarity(Q, EMBED(G')) < Similarity(Q, EMBED(RANDOM(G')))
*RANDOM means Random Graph sampling and EMBED means any selcted Graph EMBEDDING

## Methodology
Prepare latent space that generates subgraph when decoded. This will let the users to easily configure which subgraph of entire graph is required to be attended upon users' own semantic query/questions.

## Related
### Disentangled Latent Approach
### GraphVAE
