---
layout: default
---

## genome


A genome is the sum of genetic material within a cell or virion.

URI: [http://bioentity.io/vocab/Genome](http://bioentity.io/vocab/Genome)


![img](http://yuml.me/diagram/nofunky/class/[genomic entity]^-[genome], [genome]-in taxon >[organism taxon], [ontology class]^-[organism taxon])
## Mappings

 * [SO:0001026](http://purl.obolibrary.org/obo/SO_0001026)
 * [SIO:000984](http://semanticscience.org/resource/SIO_000984)
 * [WD:Q7020](http://purl.obolibrary.org/obo/WD_Q7020)

## Inheritance

 *  is_a: [genomic entity](GenomicEntity.html)

## Children



## Fields

 * [has biological sequence](has_biological_sequence.html)
    * _connects a genomic feature to its sequence_
    * __range__: biological sequence
    * inherited from: [genomic entity](GenomicEntity.html)
 * [id](id.html)
    * __range__: identifier type
    * inherited from: [named thing](NamedThing.html)
 * [label](label.html)
    * _A human-readable name for a thing_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
 * [in taxon](in_taxon.html)
    * _connects a thing to a class representing a taxon_
    * __range__: [organism taxon](OrganismTaxon.html)
    * inherited from: [thing with taxon](ThingWithTaxon.html)
