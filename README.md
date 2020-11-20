# Wikidata9M
A sequence of 9.2 million semantic triple operations extracted from Wikidata representing the change history of the ontology.
The triple operations follow the pattern:

***[Wikidata item id] [Wikidata item id] [Wikidata property id] [operation type] [timestamp]***

* The [Wikidata item id] and [Wikidata property id] are encoded without the prefixes 'Q' and 'P'. Thus, if you want to search for these items and properties 
on the Wikidata homepage keep in mind to add the corresponding prefixes.

* The [operation type] indicates whether the triple [Wikidata item id] [Wikidata item id] [Wikidata property id] has been inserted or deleted from the Wikidata 
knowledge base. Triple insertions are marked by a plus sign, i.e. [operation type] = "+". Accordingly triple deletions are marked by a minus sign, i.e [operation type] = "-".

* The [timestamp] indicates when the triple has been inserted into or deleted from Wikidata.
