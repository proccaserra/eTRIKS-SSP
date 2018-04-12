# A Business Case for Standards in eTRIKS


**IMI eTRIKS project**<sup>[1](#myfootnote1)</sup> has released a set of documents aimed at project leaders and data managers alike to provide guidance and recommendations as to which standardization efforts may be relevant to them. The work carried out by eTRIKS is meant to be made available to all IMI projects to raise awareness as well as to gain input from specific fields of translational research  and further development and refinement of data standards. Furthermore, eTRIKS aims to provide regular updates and releases, to incorporate additions and follow-ups on technology evolution and progress in standardization initiatives. eTRIKS information feeds (mailing list, website) will be used to relay these updates.

Data standards play an important role in managing and handling research data. On the one hand, regulatory agencies are increasingly mandating data standards for the submission of clinical research data and data sharing -. On the other hand, data standards encourage the use of integrated metadata, which provides a solid foundation for systematically discovering, retrieving, understanding, integrating, disseminating, exchanging and reusing research data.

Annotation resources such as MIAME guidelines or the Gene Ontology controlled vocabularies have become essential resources in modern molecular biology and computational biology. By defining how information is structured and what information is reported, standards, such as CDISC or ISA, make it easier to access, distribute, disseminate and exchange information. They also allow scientific scrutiny to be exerted, a central activity in the life of scientists. There should be no barrier to data assessment and all stakeholders of the scientific endeavour must embrace efforts aiming at enhancing access to information so it can be efficiently mined, analyzed and exploited. 	

To understand the impact of the standardization process, one should consider the roadmap set out by the European Medicines Agency for implementing a series of ISO Standards for the identification of medicinal products. The process is now widely known as the IDMP . It is an extremely significant milestone in standardization process as, starting from July 2016, Commission Implementing Regulation (EU) No 520/2012External link icon (articles 25 and 26) obliges Member States, marketing-authorisation holders and EMA to make use of the terminologies defined in ISO IDMP standards.  In practice, this means that submission to EMA, will be made using the HL7 SPL format based on the ISO IDMP standards, ISO IDMP technical specifications and HL7 common product model, a combination of standardization tools designed to supercede the eXtended EudraVigilance Product Report Message (XEVPRM) format.

Standards are developed to ensure scientific information is represented **consistently**, **efficiently** and **meaningfully** to the benefit of the community. It is expected that scientists and science stakeholders will have greater confidence when standard compliant datasets are available, ensuring data analysis and reuse in the longer term are made more straightforward.  With the use of standards the analysis of aggregated study data becomes much more reliable and effective giving maximum opportunities for medical advances and new knowledge to come to light.
More broadly, the very low data comparability and reproducibility is a big issue in Life Science, and this results in wasting significant amounts of resources in organizations worldwide, and, consequently, impairs/slows down the scientific research and the development of new drugs and biomarkers for patients. The lack of adequate reporting standards adversely affects the overall quality of available data. Therefore efforts in standardization of data, metadata and experimental/clinical reports in Life Science represent significant endeavour at rectifying this issue.
With the present document, IMI eTRIKS aims to bring about endorsement of the **FAIR principles** for data, that is to make data **‘Findable, Accessible, Interoperable and Reusable’**, as outlined by the Force 11 group. These principles are being adopted by a growing number of stakeholders, from publishers (e.g.  [NPG Scientific Data](http://www.nature.com/sdata/about/principles), to Funders and Repositories (e.g. Dryad, Figshare) to support data publication.

Finally, The entire set fo eTRIKS recommended resources can be accessed in a browseable, searcheable form from the Biosharing catalogue of standards and resources from [FAIRsharing](https://biosharing.org/collection/5?q=.)


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
The document is meant to help optimize annotation and enable translational and knowledge management applications.



## 1.3 Intended Audience
The intended audience is:
* data producers (e.g. research scientists, clinicians, patients) to raise awareness in annotation practice,
* data managers in charge of establishing data management plans to guide them in choosing which data formats and terminologies to consider and rely on when collecting new study data, preferably in standard formats.
* data quality officers responsible for ensuring procedures are adhered to and data meet expected grade.
* data curators to enable coordinated and agreed upon data cleanup and edition to eTRIKS annotation and curation guidelines,
* software developers to guide development of submission and curation tools.
* knowledge engineers and terminology managers working on developing and supporting ontologies and data models to ensure resource alignment, semantic interoperability and convergence of terminologies and data standards.

## 1.4 Standard Definition and Typology
### 1.4.1 Definition of Standards:

Standards are agreed-upon, normative conventions defined by a community of users about a group of descriptive entities, and their combinations, specific to a domain and which facilitate information exchange and communication. They can be considered as a commonly shared and accepted  criterion or specification established by authority or consensus for 1) measuring performance or quality; 2) specifying conventions that support interchange of common materials and information (for example, CDISC standards exist to support the exchange of clinical data, ISA to support exchange of omics data). Standards may act at the syntactic and/or the semantic level; both are needed to support interoperability. 

Standards should be identified by their name, their version number, the date of the last release, and, if available, a Uniform Resource Identifier (URI).
(See Section 2.2 for attributes of good standards)
### 1.4.2 Typology of Standards
Types of standards include the following: 
1. reporting requirements also called Minimum Information Guidelines (MIG); these define, usually in non-formal ways, the necessary and sufficient entities to describe a domain. eTRIKS-adopted or created MIGs will specify which exchange formats and vocabulary standards are to be used. Those content standards ensure the information exchange based on community shared meaning (semantics); they include data and metadata standards. Vocabularies are often treated separately, but they are a form of content standards and are a prerequisite to support semantic alignment.  A standard may also refer to an integration profile, an implementation guide or a user guide. 

2. vocabularies; these include a variety of terminologies, possibly multi-lingual, such as  controlled vocabularies, dictionaries/thesauri or ontologies that describe their entities, their data labels/names or their data values (i.e. text terms). 

3. exchange formats; these are syntaxes defining formal ways to structure and organize groups of entities in order to form machine readable research objects, thereby allowing data exchanges between systems and/or organizations in general.

## 1.5 Purpose of Standards
Standards are developed to increase data interoperability, reproducibility, reusability. They also support traceability/provenance, automation and process improvement and preservation/archival of information/data. Three of these major purposes are described in more details below. They are therefore essential elements for ensuring delivering FAIR datasets.

* __Accessibility & long term preservation__: Data live beyond projects, consortia, or organizations. Standards allow for legacy data to be mobilized years after their creation, and compared with more recent or updated datasets. Standards ensure datasets are preserved in well documented, possibly self-describing, data structures. The notion of accessibility includes issues related to data protection and patient privacy. Therefore, information governing access permission, patient consent and encryption need to be described in standardized ways. 

* Interoperability:  To enable operational processes which underlie data exchange and sharing between different software systems. Two distinct facets of interoperability need to be addressed simultaneously to reach efficiency. One dimension covers the syntactic alignment, which can be viewed as a more technical layer. The second dimension concerns itself with the meaningfulness of interoperation, something designated as ‘semantic interoperability’.

* Reusability: Conformance to standards ensures reliable and consistent description of information (both in structure and content), making it easier to develop robust software for exchanging data payload to be exploited by computational systems. Therefore, standards make data (and research objects) more usable, re-usable, and comparable across studies and/or organizations. Reusability is a central aspect of data preservation, working on the premises that dataset availability should allow meta analysis and discovery through data aggregation. Furthermore, good annotation standards lead to a higher reliability of meta-analysis results by better selecting data from different studies for those meta-analyses.

* Reproducibility: Reporting standards enable to evaluate data quality, to ascertain solidity of claims and findings. They are therefore invaluable resources, as they allow information to be assessed. On the one hand, reporting standards, by making key requirements explicit, allow for instance in the case of experimental information testing for confounding factors, thus enhancing reassessment and reproducibility. On the other hand, information provenance standards provide the means to records events to the data artefacts itself and the chain of custody associated with it. Both types contribute to good data stewardship. 




<a name="myfootnote1">1</a>: "What is eTRIKS..." 2012. 6 Jun. 2015  (http://www.etriks.org/)

