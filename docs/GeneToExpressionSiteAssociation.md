---
layout: default
---

## gene to expression site association


An association between a gene and an expression site, possibly qualified by stage/timing info.

URI: [http://bioentity.io/vocab/GeneToExpressionSiteAssociation](http://bioentity.io/vocab/GeneToExpressionSiteAssociation)


![img](http://yuml.me/diagram/nofunky/class/[association]^-[gene to expression site association], [gene to expression site association]-stage qualifier >[life stage], [organismal entity]^-[life stage], [life stage]-in taxon >[organism taxon], [ontology class]^-[organism taxon], [gene to expression site association]-quantifier qualifier >[ontology class], [gene to expression site association]-association type >[ontology class], [gene to expression site association]-subject >[gene or gene product], [genomic entity]^-[gene or gene product], [gene or gene product]-in taxon >[organism taxon], [gene to expression site association]-relation >[relationship type], [gene to expression site association]-object >[anatomical entity], [organismal entity]^-[anatomical entity], [anatomical entity]-in taxon >[organism taxon], [gene to expression site association]-qualifiers >[ontology class], [gene to expression site association]-publications >[publication], [information content entity]^-[publication], [gene to expression site association]-provided by >[provider], [administrative entity]^-[provider])
## Mappings


## Inheritance

 *  is_a: [association](Association.html)

## Children



## Fields

 * [stage qualifier](stage_qualifier.html)
    * _stage at which the gene is expressed in the site_
    * __range__: [life stage](LifeStage.html)
    * Example: [UBERON:0000069](http://purl.obolibrary.org/obo/UBERON_0000069) larval stage
    * __Local__
 * [quantifier qualifier](quantifier_qualifier.html)
    * _can be used to indicate magnitude, or also ranking_
    * __range__: [ontology class](OntologyClass.html)
    * __Local__
 * [association type](association_type.html)
    * _connects an association to the type of association (e.g. gene to phenotype)_
    * __range__: [ontology class](OntologyClass.html)
    * inherited from: [association](Association.html)
 * [subject](subject.html)
    * _gene in which variation is correlated with the phenotypic feature_
    * __range__: [gene or gene product](GeneOrGeneProduct.html) [required]
    * inherited from: [association](Association.html)
 * [negated](negated.html)
    * _if set to true, then the association is negated i.e. is not true_
    * __range__: xsd:boolean
    * inherited from: [association](Association.html)
 * [relation](relation.html)
    * _expression relationship_
    * __range__: [relationship type](RelationshipType.html) [required]
    * subproperty_of: [RO:0002206](http://purl.obolibrary.org/obo/RO_0002206)
    * inherited from: [association](Association.html)
 * [object](object.html)
    * _location in which the gene is expressed_
    * __range__: [anatomical entity](AnatomicalEntity.html) [required]
    * Example: [UBERON:0002037](http://purl.obolibrary.org/obo/UBERON_0002037) cerebellum
    * inherited from: [association](Association.html)
 * [qualifiers](qualifiers.html)
    * _connects an association to qualifiers that modify or qualify the meaning of that association_
    * __range__: [ontology class](OntologyClass.html)*
    * inherited from: [association](Association.html)
 * [publications](publications.html)
    * _connects an association to publications supporting the association_
    * __range__: [publication](Publication.html)*
    * inherited from: [association](Association.html)
 * [provided by](provided_by.html)
    * _connects an association to the agent (person, organization or group) that provided it_
    * __range__: [provider](Provider.html)
    * inherited from: [association](Association.html)
 * [id](id.html)
    * __range__: identifier type [required]
    * inherited from: [named thing](NamedThing.html)
 * [label](label.html)
    * _A human-readable name for a thing_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
