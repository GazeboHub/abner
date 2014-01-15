
abner
=====

## Overview

[Abner][abner] is developed as a Java toolkit for processing Planetary Data Set (PDS) files as published by NASA JPL

### Naming

The [Abner][abner] project is named after a character from the _Pelucidar_ series of books, authored by Edgar Rice Burroughs. _Milestones_ in the project are named after characters from the first book in the series, _At the Earth's Core_.

## Project Roadmap

#### Milestone M1 - "Ghak"

Goals:

* Develop a domain-specific grammar for processing the PDS files
* Develop procedures for creating Hibernate ORM mappings from the PDS files

Use Cases:

* Successfully load the [EAR-A-5-DDR Asteroid Taxonomy 6.0][EAR-A-5]

Reference Information:

* _[PDS Standards Reference][pds-std]_, version _3.8_

#### Milestone M2 - "Hooja"

Goals:

* Develop procedures for deriving a bigliographically annotated ontology from an input PDS data set
 
Use Cases:

* Derive an ontology of asteroid classifications from the [EAR-A-5-DDR Asteroid Taxonomy 6.0][EAR-A-5]
 
Reference Information:

* _[Apache Jena][jena]_
* _[Protege][protege]_
* _[Web Protege][web-protege]_
* _[OWL 2 Web Ontology Language Primer]_
* _[SPAR Ontolgoies][spar]_ (tenative)

#### Milestone M3 (Tentative) - "Dian" 

Goals:

* Develop extensions onto the Eclipse IDE for viewing and processing of PDS data sets

Use cases:

* TBD


[abner]: https://github.com/GazeboHub/abner
[EAR-A-5]: http://sbn.psi.edu/pds/resource/taxonomy.html
[pds-std]: http://pds.jpl.nasa.gov/tools/standards-reference.shtml
[jena]: http://jena.apache.org/
[protege]: http://protege.stanford.edu/
[web-protege]: http://protegewiki.stanford.edu/wiki/WebProtege
[owl2-primer]: http://www.w3.org/TR/2009/REC-owl2-primer-20091027/
[spar]: http://opencitations.wordpress.com/2010/10/14/introducing-the-semantic-publishing-and-referencing-spar-ontologies/
