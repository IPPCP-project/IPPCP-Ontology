# Emissions Inventory Ontology

The Emissions Inventory Ontology (EIO) provides a semantic model for representing emissions inventory data in urban and territorial contexts.

The ontology describes emission measurements and assessments by connecting the emitted pollutant, emission sector, geographical feature, reporting period, numerical value, and unit of measurement.

EIO reuses concepts and properties from established vocabularies, including SAREF, SAREF4CITY, OWL-Time, GEOSPARQL, and QUDT.

# Purpose and scope of the vocabulary

The purpose of the Emissions Inventory Ontology is to provide a common and machine-readable representation of emissions inventory data. It supports the integration, publication, comparison, and querying of emission data originating from different geographical areas, reporting periods, pollutants, and economic or activity sectors.

The ontology enables the representation of:

- Emission assessments as instances of s4city:KeyPerformanceIndicatorAssessment.
- The pollutant or emission indicator quantified by an assessment.
- The sector or subsector responsible for the emissions.
- Geographical features such as cities, districts, and spatial cells.
- The reporting period associated with an emission assessment.
- Numerical emission values and their units of measurement.

# Ontology prefix and namespace

The Emissions Inventory Ontology prefix is: eio and it is published under the namespace: [http://w3id.org/def/emissionsInventoryOntology#
]([url](http://w3id.org/def/emissionsInventoryOntology#))

# Ontology Conceptualization Image

The following diagram provides a visual representation of the main concepts and relationships included in the Emissions Inventory Ontology:

![Ontology Conceptualization Diagram](diagrams/diagram.png)

# Reposity structure

The repository should contain (at least) the following folders:

| Folder                  | Description                                                                                                                                      |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **diagrams/**     | Stores diagrams and other resources representing the conceptual model of the ontology (e.g., class hierarchies, relationships).                  |
| **Ontoology/**    | Stores the HTML or human oriented documentation of the ontology and related artefacts.                                                           |
| **examples/**     | Includes examples that demonstrate how to instantiate or apply the ontology in real data scenarios.                                              |
| **ontology/**     | Contains the actual ontology implementation files in formats such as`.owl`, `.rdf`, `.ttl`, or `.jsonld`.                                |
| **requirements/** | Contains all documents used to define the ontology’s requirements: data example, competency questions, functional requirements, use cases, etc. |
|                         |                                                                                                                                                  |

# Project maintenance

To manage those incidents or suggested improvements with respect to the vocabulary, we recommend you to follow
the guides provided in [Issues Management](https://github.com/nombre-repositorio/wiki/issues-management) to
generate an issue (work in progress)

# Acknowledgements

This project has been funded by the European Union's European Data Space far Smart Communities - DS4SSCC-DEP action under grant agreement no.101123342 in the Digital Europe Programme as part of the Piloting Programme in relation to the Project 2025-3-1 - IPPCP.

<img height="100" alt="logo-color" src="https://github.com/user-attachments/assets/50712b11-ec2d-4947-8313-a35ffe94fd5d" /> <img src="https://images.squarespace-cdn.com/content/v1/63718ba2d90d0263d7fc1857/415e1aec-464c-4e5a-aa59-4e11ee295281/Logo+Color-min.png?format=300w" height="80"/> <img height="80" alt="EN_Co-fundedbytheEU_RGB_POS" src="https://github.com/user-attachments/assets/826c43cb-e649-436b-be92-1940da9d21fd" />
