---
layout: default
---

## gene to phenotypic feature association


None

URI: [http://bioentity.io/vocab/GeneToPhenotypicFeatureAssociation](http://bioentity.io/vocab/GeneToPhenotypicFeatureAssociation)


![img](http://yuml.me/diagram/nofunky/class/[association]^-[gene to phenotypic feature association], [gene to phenotypic feature association]-association type >[ontology class], [gene to phenotypic feature association]-subject >[gene or gene product], [genomic entity]^-[gene or gene product], [gene or gene product]-in taxon >[organism taxon], [ontology class]^-[organism taxon], [gene to phenotypic feature association]-relation >[relationship type], [gene to phenotypic feature association]-object >[phenotypic feature], [disease or phenotypic feature]^-[phenotypic feature], [phenotypic feature]-in taxon >[organism taxon], [gene to phenotypic feature association]-qualifiers >[ontology class], [gene to phenotypic feature association]-publications >[publication], [information content entity]^-[publication], [gene to phenotypic feature association]-provided by >[provider], [administrative entity]^-[provider], [gene to phenotypic feature association]-frequency qualifier >[frequency value], [attribute]^-[frequency value], [gene to phenotypic feature association]-severity qualifier >[severity value], [attribute]^-[severity value], [gene to phenotypic feature association]-onset qualifier >[onset], [attribute]^-[onset], [gene to phenotypic feature association]-sex qualifier >[biological sex], [attribute]^-[biological sex])
## Mappings

 * [http://bio2rdf.org/wormbase_vocabulary:Gene-Phenotype-Association](http://purl.obolibrary.org/obo/http_//bio2rdf.org/wormbase_vocabulary_Gene-Phenotype-Association)

## Inheritance

 *  is_a: [association](Association.html)
 *  mixin: [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
 *  mixin: [gene to thing association](GeneToThingAssociation.html)

## Children



## Fields

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
    * _the relationship type by which a subject is connected to an object in an association_
    * __range__: [relationship type](RelationshipType.html) [required]
    * inherited from: [association](Association.html)
 * [object](object.html)
    * _phenotypic class_
    * __range__: [phenotypic feature](PhenotypicFeature.html) [required]
    * Example: [HP:0002487](http://purl.obolibrary.org/obo/HP_0002487) Hyperkinesis
    * Example: [WBPhenotype:0000180](http://purl.obolibrary.org/obo/WBPhenotype_0000180) axon morphology variant
    * Example: [MP:0001569](http://purl.obolibrary.org/obo/MP_0001569) abnormal circulating bilirubin level
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
 * [frequency qualifier](frequency_qualifier.html)
    * _a qualifier used in a phenotypic association to state how frequent the phenotype is observed in the subject_
    * __range__: [frequency value](FrequencyValue.html)
    * inherited from: [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
 * [severity qualifier](severity_qualifier.html)
    * _a qualifier used in a phenotypic association to state how severe the phenotype is in the subject_
    * __range__: [severity value](SeverityValue.html)
    * inherited from: [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
 * [onset qualifier](onset_qualifier.html)
    * _a qualifier used in a phenotypic association to state when the phenotype appears is in the subject_
    * __range__: [onset](Onset.html)
    * inherited from: [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
 * [sex qualifier](sex_qualifier.html)
    * _a qualifier used in a phenotypic association to state whether the association is specific to a particular sex._
    * __range__: [biological sex](BiologicalSex.html)
    * inherited from: [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
