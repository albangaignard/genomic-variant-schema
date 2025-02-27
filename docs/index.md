# gvar

Schema for describing genomic variants as organised in a VCF file.
This is not a representation of a VCF in RDF.
This is a representation of genomic variants as Linked Data.  

URI: https://ican.univ-nantes.io/genomic-variants-schema/

Name: gvar



## Classes

| Class | Description |
| --- | --- |
| [AlternateAllele](AlternateAllele.md) | Represents the alternate allele (geno:0000002). |
| [Container](Container.md) | None |
| [ReferenceAllele](ReferenceAllele.md) | Represents the reference allele (geno:0000036). |
| [SequenceAlteration](SequenceAlteration.md) | A representation of a sequence alteration (so:0001059). |
| [VariantIdentifier](VariantIdentifier.md) | A unique identifier for a sequence alteration. |
| [VariationSite](VariationSite.md) | Represents the location of a sequence alteration. |
| [VariationSiteBegin](VariationSiteBegin.md) | Represents the beginning of the location of a sequence alteration. |
| [VariationSiteEnd](VariationSiteEnd.md) | Represents the end of the location of a sequence alteration. |
| [VariationSiteReference](VariationSiteReference.md) | Represents the reference sequence (contig, sequence, chromosome). |



## Slots

| Slot | Description |
| --- | --- |
| [begins_at](begins_at.md) | The beginning of the location of the sequence alteration |
| [ends_at](ends_at.md) | The end of the location of the sequence alteration |
| [has_alternate_allele](has_alternate_allele.md) | Links the sequence alteration to its alternate allele |
| [has_identifier](has_identifier.md) | A unique identifier for the sequence alteration |
| [has_location](has_location.md) | Links the sequence alteration to its location |
| [has_reference](has_reference.md) | The reference sequence (contig, sequence, chromosome) |
| [has_reference_allele](has_reference_allele.md) | Links the sequence alteration to its reference allele |
| [has_zygosity](has_zygosity.md) | The zygosity of the sequence alteration |
| [hgvsid](hgvsid.md) | HGVSid |
| [label](label.md) | A human-readable label for the reference sequence |
| [other](other.md) | Other identifiers |
| [position](position.md) | The position of the beginning of the location of the sequence alteration |
| [rsid](rsid.md) | dbsnp rsid |
| [sameAs](sameAs.md) | The value of the reference sequence in another database (ncbi sequence i |
| [value](value.md) | The value of the reference allele |
| [variantcatalog](variantcatalog.md) |  |


## Enumerations

| Enumeration | Description |
| --- | --- |
| [ZygosityType](ZygosityType.md) | Enumeration of zygosity types |


## Types

| Type | Description |
| --- | --- |
| [Boolean](Boolean.md) | A binary (true or false) value |
| [Curie](Curie.md) | a compact URI |
| [Date](Date.md) | a date (year, month and day) in an idealized calendar |
| [DateOrDatetime](DateOrDatetime.md) | Either a date or a datetime |
| [Datetime](Datetime.md) | The combination of a date and time |
| [Decimal](Decimal.md) | A real number with arbitrary precision that conforms to the xsd:decimal speci... |
| [Double](Double.md) | A real number that conforms to the xsd:double specification |
| [Float](Float.md) | A real number that conforms to the xsd:float specification |
| [Integer](Integer.md) | An integer |
| [Jsonpath](Jsonpath.md) | A string encoding a JSON Path |
| [Jsonpointer](Jsonpointer.md) | A string encoding a JSON Pointer |
| [Ncname](Ncname.md) | Prefix part of CURIE |
| [Nodeidentifier](Nodeidentifier.md) | A URI, CURIE or BNODE that represents a node in a model |
| [Objectidentifier](Objectidentifier.md) | A URI or CURIE that represents an object in the model |
| [Sparqlpath](Sparqlpath.md) | A string encoding a SPARQL Property Path |
| [String](String.md) | A character string |
| [Time](Time.md) | A time object represents a (local) time of day, independent of any particular... |
| [Uri](Uri.md) | a complete URI |
| [Uriorcurie](Uriorcurie.md) | a URI or a CURIE |


## Subsets

| Subset | Description |
| --- | --- |
