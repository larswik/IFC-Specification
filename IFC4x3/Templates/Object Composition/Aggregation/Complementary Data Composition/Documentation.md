Provision of an aggregation structure where the complementary data is part of another complementary data representing the composite. The part then provides, if such concepts are in scope of the Model View Definition, exclusively the following:

* _Body Geometry_ &mdash; The partial body shape representation and its placement;
* _Material_ &mdash; The material information for the part.

The part may also provide, in addition to the aggregate, more specifically the following:

* _Property Sets_ &mdash; The parts may have individual property sets assigned, solely or in addition to the composite;
* _Quantity Sets_ &mdash; The parts may have individual quantity sets assigned, solely or in addition to the composite.

The part should not be contained in the spatial hierarchy, i.e. the concept _Spatial Containment_ shall not be used at the level of parts. The part is contained in the spatial structure by the spatial containment of its composite.

The part should not be assigned to an _IfcProduct_, i.e. the concept _Product Assignment_ shall not be used at the level of parts.

> EXAMPLE&nbsp; An _IfcComplementaryData_ may be aggregated into a composite _IfcComplementaryData_ using the objectified relationship _IfcRelAggregates_, refering to it by its inverse attribute SELF\IfcObjectDefinition.Decomposes. Any subtype of _IfcComplementaryData_ can be an element assembly. In this case it should not be additionally contained in the spatial hierarchy, i.e. _SELF\IfcElement.ContainedInStructure_ should be NIL.
