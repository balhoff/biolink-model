---
layout: default
---

## noncoding RNA product


None

URI: [http://bioentity.io/vocab/NoncodingRnaProduct](http://bioentity.io/vocab/NoncodingRnaProduct)


![img](http://yuml.me/diagram/nofunky/class/[RNA product]^-[noncoding RNA product], [noncoding RNA product]-in taxon >[organism taxon], [ontology class]^-[organism taxon])
## Mappings

 * [SIO:001235](http://semanticscience.org/resource/SIO_001235)

## Inheritance

 *  is_a: [RNA product](RnaProduct.html)

## Children

 *  child: [microRNA](Microrna.html)


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
