# Part 1. Introduction
 
## 1.1 eTRIKS mission and objectives

eTRIKS aims to provide a reference point for data management standards relevant to scientific research focusing on translational medicine in order to make the most of advances of animal model, in-vitro and clinical experimentation. Recommendations are needed to provide guidance in wide array of specifications available, produced both by academics and standard development organizations (SDO).

 Among the goals of eTRIKS are:
* Standard harmonization for data annotation. Common list of eTRIKS-selected and recommended standards for data owners, curators and consumers.
* Standard facilitation. “Bridge builder" between standards communities. Break the silos and facilitate communication between standard communities to drive out duplication and competing standards.
* Reporting standard creation. When not existing, leverage on the technological, medical and laboratory expertise across IMI consortia to develop common reporting standards.
* Standard adoption. Increase the adoption of standards by contributing to the development of annotation tools. 
* Data preservation. Contribute to the development of eTRIKS repository that enables the preservation of standardized data through automatic standard updates
Turning data into knowledge. Contribute to the development of eTRIKS metadata registry and semantic layer that enable smart data searches and inferences.

## 1.2 Document objective
This document aims to inform readers about eTRIKS guidelines and procedures dealing with data standards and stewardship of standards. eTRIKS strongly recommends eTRIKS collaborators to follow these guidelines when applicable, in order to facilitate and increase data reusability, reproducibility, and preservation.
The document is meant to help optimize annotation and enable _translational and knowledge management applications_.

## 1.3 Intended Audience
The intended audience is:
* **data producers** (e.g. research scientists, clinicians, patients) to raise awareness in annotation practice,
* **data managers** in charge of establishing data management plans to guide them in choosing which data formats and terminologies to consider and rely on when collecting new study data, preferably in standard formats.
* **data quality officers** responsible for ensuring procedures are adhered to and data meet expected grade.
* **data curators** to enable coordinated and agreed upon data cleanup and edition to eTRIKS annotation and curation guidelines,
* **software developers** to guide development of submission and curation tools.
* **knowledge engineers and terminology managers** working on developing and supporting ontologies and data models to ensure resource alignment, semantic interoperability and convergence of terminologies and data standards.

## 1.4 Standard Definition and Typology
### 1.4.1 Definition of Standards:

_Standards_ are agreed-upon, normative conventions defined by a community of users about a group of descriptive entities, and their combinations, specific to a domain and which facilitate information exchange and communication. They can be considered as a commonly shared and accepted  criterion or specification established by authority or consensus for 1) measuring performance or quality; 2) specifying conventions that support interchange of common materials and information (_for example, CDISC standards exist to support the exchange of clinical data, ISA to support exchange of omics data_). Standards may act at the syntactic and/or the semantic level; both are needed to support interoperability. 

Standards should be identified by their name, their version number, the date of the last release, and, if available, a Uniform Resource Identifier (URI).
**(See Section 2.2 for attributes of good standards)**

### 1.4.2 Typology of Standards
Types of standards include the following: 
1. _**reporting requirements** also called **Minimum Information Guidelines (MIG)**_; these define, usually in non-formal ways, the necessary and sufficient entities to describe a domain. eTRIKS-adopted or created MIGs will specify which exchange formats and vocabulary standards are to be used. Those content standards ensure the information exchange based on community shared meaning (semantics); they include data and metadata standards. Vocabularies are often treated separately, but they are a form of content standards and are a prerequisite to support semantic alignment.  A standard may also refer to an integration profile, an implementation guide or a user guide. 

2. _**vocabularies**_; these include a variety of terminologies, possibly multi-lingual, such as  controlled vocabularies, dictionaries/thesauri or ontologies that describe their entities, their data labels/names or their data values (i.e. text terms). 

3. _**exchange formats**_; these are syntaxes defining formal ways to structure and organize groups of entities in order to form machine readable research objects, thereby allowing data exchanges between systems and/or organizations in general.

## 1.5 Purpose of Standards
Standards are developed to increase data interoperability, reproducibility, reusability. They also support traceability/provenance, automation and process improvement and preservation/archival of information/data. Three of these major purposes are described in more details below. They are therefore essential elements for ensuring delivering **FAIR datasets**.

* **Accessibility & long term preservation**: Data live beyond projects, consortia, or organizations. Standards allow for legacy data to be mobilized years after their creation, and compared with more recent or updated datasets. Standards ensure datasets are preserved in well documented, possibly self-describing, data structures. The notion of accessibility includes issues related to data protection and patient privacy. Therefore, information governing access permission, patient consent and encryption need to be described in standardized ways. 

* **Interoperability**:  To enable operational processes which underlie data exchange and sharing between different software systems. Two distinct facets of interoperability need to be addressed simultaneously to reach efficiency. One dimension covers the syntactic alignment, which can be viewed as a more technical layer. The second dimension concerns itself with the meaningfulness of interoperation, something designated as ‘semantic interoperability’.

* **Reusability**: Conformance to standards ensures reliable and consistent description of information (both in structure and content), making it easier to develop robust software for exchanging data payload to be exploited by computational systems. Therefore, standards make data (and research objects) more usable, re-usable, and comparable across studies and/or organizations. Reusability is a central aspect of data preservation, working on the premises that dataset availability should allow meta analysis and discovery through data aggregation. Furthermore, good annotation standards lead to a higher reliability of meta-analysis results by better selecting data from different studies for those meta-analyses.

* **Reproducibility**: Reporting standards enable to evaluate data quality, to ascertain solidity of claims and findings. They are therefore invaluable resources, as they allow information to be assessed. On the one hand, reporting standards, by making key requirements explicit, allow for instance in the case of experimental information testing for confounding factors, thus enhancing reassessment and reproducibility. On the other hand, information provenance<sup>[14](#myfootnote14)</sup>  standards provide the means to records events to the data artefacts itself and the chain of custody associated with it. Both types contribute to good data stewardship. 




---------------
<sub>
<a name="myfootnote1">1</a>: "What is eTRIKS?" 2012. 6 Jun. 2015  (http://www.etriks.org/)

<a name="myfootnote2">2</a>: "Innovative Medicines Initiative: Home IMI." 2007. 6 Jun. 2015 (http://www.imi.europa.eu/)

<a name="myfootnote3">3</a>: "NIH Data Sharing Policy - National Institutes of Health." 2002. 6 Jun. 2015 (http://grants.nih.gov/grants/policy/data_sharing/)


<a name="myfootnote4">4</a>: "An essential guide to open access for Wellcome Trust ..." 2011. 8 Jun. 2015 (https://goo.gl/oPijMD)


<a name="myfootnote5">5</a>: Brazma, Alvis et al. "Minimum information about a microarray experiment (MIAME)—toward standards for microarray data." Nature genetics 29.4 (2001): 365-371.

<a name="myfootnote6">6</a>: Ashburner, Michael et al. "Gene Ontology: tool for the unification of biology." Nature genetics 25.1 (2000): 25-29.

<a name="myfootnote7">7</a>: "CDISC, Strength Through Collaboration." 6 Jun. 2015 (http://www.cdisc.org/)

<a name="myfootnote8">8</a>: "ISA Tools." 2005. 6 Jun. 2015 (http://www.isa-tools.org/)


<a name="myfootnote9">9</a>: "Implementation of the ISO IDMP standards - European ..." 2015. 14 Mar. 2016 (https://goo.gl/K47AEW)


<a name="myfootnote10">10</a>: Mobley, A. "A Survey on Data Reproducibility in Cancer Research ..." 2013. (http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0063221)

<a name="myfootnote11">11</a>: "The FAIR Data Principles - FOR COMMENT - FORCE11." 2014. 6 Mar. 2016 (https://www.force11.org/group/fairgroup/fairprinciples)

<a name="myfootnote12">12</a>: "Dryad Digital Repository - Dryad." 2008. 10 Mar. 2016 (http://datadryad.org/)

<a name="myfootnote13">13</a>: "figshare - credit for all your research." 2012. 10 Mar. 2016 (https://figshare.com/)

<a name="myfootnote14">14</a>: "What Is Provenance - XG Provenance Wiki." 2010. 19 Jun. 2015 (http://www.w3.org/2005/Incubator/prov/wiki/What_Is_Provenance)

</sub>

