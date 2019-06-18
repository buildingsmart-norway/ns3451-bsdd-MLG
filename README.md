# ns3451-bsdd-MLG
Repository for a test on retrieving NS3451:2009 in bSDD, create taxonomy based on MLG and write to .ttl file.

## Use of Modelling and Linking Guide CEN 442 WG4 TG3

In order to harmonize the approch of modelling and linking ontologies, CEN 442 WG4 TG3 is proposing a Modelling and Linking Guide (MLG). The MLG idea comes from the Interlink project, [please see this video for an introduction](https://www.youtube.com/embed/aKlc4Cj9lmw)

It contains three different levels, where Level 1 proposes choices for modelling Taxonomies. NS3451 is a Norwegian taxonomy of building elements [Bygningsdelstabellen](https://www.standard.no/fagomrader/bygg-anlegg-og-eiendom/ns-3420-/ns-3450----ns-3451---ns-3459-2/). I is also uploaded to bSDD and related through an open "context" named Standard Norway [Link to the top node here](http://bsdd.buildingsmart.org/#concept/details/3qhov7DEn0ORoAeFXLyfC3).

## bSDD Contexts to ontologies
When writing the ontology each concept has the seeAlso link to the bSDD Dictionary containing also the bSDD Guid.

This way it also creates a way of linking to concepts in the dictionary. Other versions of NS3451 could also be linked to.

## How to use the code in the Repository

This project uses python 3 and jupyter notebooks. For accessing bSDD the request library is used, and for working with the ontology the RDFLib library is used.

The [environment.yml](environment.yml). Install anaconda on your machine [create environment from this file](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file). After you can activate it by source activate {name of environment} and start the notebooks by ```jupyter notebook``` in the repo root.

## How to contribute
Please add an issue with ideas or comments, and feel free to add pull requests with alterations.

## File result
Please see the ns3451-skos.ttl for a result of the script.

It could be viewed and edited in eg. [Protegé downloadable here](https://protege.stanford.edu/)
