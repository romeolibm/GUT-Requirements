# GUT-Requirements (under development)
Basic requirements for data architecture and tools implementation for building a GUT (Global Universal Taxonomy) and the LUT (Local Universal Taxonomy)

This document uses the following names:

|Name|Description|
|----|---|
|GUT|Global Universal Taxonomy|
|LUT|Local Universal Taxonomy|
|NSID|Name-Space unique binary ID|
|WORM|Write Once Read Many|

# Requirements for GUT and LUT entities

1. There can be only one GUT in this reality
2. The GUT and LUTs have assigned binary namespaces identified in by unique (relative to the GUT) 64 bit random numbers
3. The GUT NSID is equal to 1
4. The GUT and LUT entities are human language independent
5. Connecting GUT/LUT entities to human lanaguages is done via Labels, names and symbols that can be linked to GUT/LUT entities
6. The GUT is built from LUTs by using well defined publishing and merging procedures from all people and groups of people on earth
7. The GUT is a public open shared repository of information used to describe entities from both the real and imaginary domains by using binary identities for all entities used to describe an entity such as base entities and their attributes (or parameters, etc)
8. Each human or group of humans can create and maintin one or more LUTs they can publish to the GUT without impacting the GUT or other LUTs bcause of unique NSIDs and WORM object architecture 
9. The uniqueness of a LUT NSIDs is verified against the list of LUT namespaces registered in the GUT repository
10. LUT NSID can be anonimized
11. The GUT entity structures are fully defined via a set of 3 dimension T-uples (ent-id,attr-id,component-d/atomic-value)
12. Connecting LUTs to The GUT are done via LUT-GUT identity mapping that allows for independent binary namespaces for the GUT and any LUT out there
13. This repository will define a minimal core set of entities that will be used to define basic entities and structures in any LUT in order to bootstrap the process of building LUTs and in time consolidating them in the GUT
14. The core set of entities will be fully documented in this repository
15. The first entity of the GUT is the "root" entity, a fully abstract entity that serves only as an initial anchor (or starting point for any other entity in a LUT directoy or indirectly via inheritance
16. ?

|ID|Description|
|---|---|
|0|Default best replacement, used only for root entities that need a spacial placeholder for not yet defined entities|
|1|The root entity is the entity all other entities are derived from. It is seldomly used outside of this core definitiion. Use higher entities to derive your entity definitions|
|2|This is the id for a completely generic entity attribute relation identifier (second id in the RDF tuple. Used as is as a relation descriptor, it means is-a, or extends|
|3|Real Entity, something from the real world, measurable|
|4|Imaginary entity, this is not real, it exists only in our imagination, hipotheses, math, models etc all are derived from this entity|
|5|An attribute class that indicates that the target is a endelable part of the defined entity, a feature (can't be removed without destroying the defined entity)|
|6|An attribute class that indicates that the target belongs to the defined entity but the relationship can be broken without destroying the entity| 
|7|An attrribute type describing the target as an attribute pointing to a leaf target (a target that is not an identifier but data to be interpreted in few fundamental ways)|
|8|An attrribute type describing the target as a boolean entity, it can have only two values and is usually one bit long aligned to the local CPU word or one byte 0/1|
|9|An attrribute type describing the target as a natural (unsigned) integral number of unlilmited size (but usually limited to < 4kB length)|
|10|An attrribute type describing the target as (signed) integral number of unlilmited size (but usually limited to < 4kB length)|
|11|An attrribute type describing the target as floating point number|
|12|An attrribute type describing the target as an array of symbols, where the encoding is only specified in the derived entity|
|13|An attrribute type describing the target as an array of symbols extends #11 with encoding 4 byte UNICODE|
|14|An attrribute type describing the target as an array of symbols extends #11 with encoding UTF-8|

## Related work

 * [UESI Universal Editor for Structured Information](https://github.com/romeolibm/UESI)
 * ...
