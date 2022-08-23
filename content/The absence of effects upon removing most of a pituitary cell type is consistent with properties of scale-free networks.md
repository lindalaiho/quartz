### Evidence that removing large proportions of pituitary cell types does not majorily affect phenotype
- [Waite 2010](https://doi.org/10.1210/en.2009-0539) deleted different proportions of somatotrophs and showed that moderate deletions have no major phenotypes
- [Roose 2017](https://doi.org/10.1038/s41598-017-16796-2) found that deleting most Sox2+ve cells produced no major effects on the rest of the pituitary cell types

### In random networks there is a threshold where node removal isolates network components and where functional consequences appear but scale-free networks exhibit robustness to random node failures
- Evidence: [Barabasi 2016](http://networksciencebook.com/) chapter 8
- You have to remove almost all nodes to break apart a scale-free network
- This is bc a scale-free network has so many more small-degree nodes than hubs so that random node selection almost always targets a small-degree node, leaving the hubs intact

### Link removal in scale-free networks is similarly robust as node removal
- Evidence: [Barabasi 2016](http://networksciencebook.com/) chapter 8
- You also have to remove almost all links before the connectivity breaks apart
- THEORY: so is this why there are so many paracrine interactions?

### HOWEVER, in real networks, node/link removal is not usually random but we have cascading failure
- This makes sense since pituitary cells need to make hormones and if one stops the others have to work harder to produce more hormone

### How do we build networks that optimise robustness against random failures and targeted attacks without increasing the cost (i.e. adding loads of links)?
- Answer: have a hub-and-spoke topology [Barabasi 2016](http://networksciencebook.com/)
- But most networks are scale-free and don't have hub-and-spoke topology, suggesting that robustness is not the principle that drives the existence of networks, it just happens that they also have robustness
