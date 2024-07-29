# Relationship-Based Access Control
Relationship Based Access Control (ReBAC) allows the definition of relationships 
between users and objects, e.g., `User A is owner of Object 1`, relationships 
between objects and other objects, e.g., `Object 1 is parent of Object 2`, and relationships 
between groups of users and objects e.g., `Owners of an Object are owners of their children`. Then, 
authorization checks are queries of the form of 
`does user U have relation R to object O?` ReBAC provides a uniform data model and language for expressing 
a wide range of access control policies that can scale to a large number of entities and 
services. Key features include retaining consistency and causal ordering when access 
control policies or object properties change.  