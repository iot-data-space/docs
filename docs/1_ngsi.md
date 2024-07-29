# The NGSI-LD API
Our data space implements the ETSI's NGSI-LD API<sup>1</sup>. This API allows access 
to `attributes` of objects representing real world assets. The attributes of an object
are defined by the object `type`. For example, our broker includes information about
objects representing devices performing energy related measurements. Therefor in
our system there are objects of type `meter` that have attributes such as `name`, `location`,
`consumption`.


<sup>1</sup> Context Information Management (CIM) ETSI ISG. 2022. NGSI-LD API.
Group Specification CIM-009v161. ETSI