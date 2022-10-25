VSSO Next
=========

This is a proposal to change the structure of the VSSO-Core ontology,
in an attempt to respond to https://github.com/w3c/vsso/issues/22

It is composed of the following files:

* [vsso-next-core.ttl](vsso-next-core.ttl) contains the new structure for VSSO-Core
  (it is not complete, and the names of the classes and properties are not definitive)
* [vsso-next.ttl](vsso-next.ttl) containes a tiny part of what VSSO would look
  like with the new proposed VSSO-Core
* [vsso-next.drawio.svg](vsso-next.drawio.svg) provides a graphical representation
  of the previous two files
* [vsso-next-instances.ttl](vsso-next-instances.ttl) contains a set of example
  instances, demonstrating how the new VSSO could be used
* [vsso-next-instances.drawio.svg](vsso-next-instances.drawio.svg) contains a set of
  example instances, demonstrating how the new VSSO could be used

NB: the focus for the moment is on encoding the VSS hierarchy of components in a way that is both semantically correct and easier to use than the current modelling (instances vs. classes).

It is totally agnostic to how static vs. dynamic properties are represented.
