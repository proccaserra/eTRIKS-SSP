# Part 2. Procedure for standards selection and recommendation
## 2.1 Procedure outline

As recommended by the eTRIKS Standards Advisory Board (as of January 28th, 2014), the selection and use of standards should be as objective, practical, and useful as possible. Information standards should be selected based on the available metadata. Practical applicability and sustainability of a standard rather than its completeness are preferred.

eTRIKS goal is to make recommendations of which standards should be used and in which domain. eTRIKS will demonstrate the benefits and applicability of the adoption of standards using practical examples of real use cases with supported projects. Over time, the goal is to track the use and adoption of said standards using simple metrics, such as how many times they have been used in projects and how good the coverage was for the projects supported.

Where practical the following criteria are used to assess whether to adopt a standard, and which one where competing standards exists.

## 2.2 Attributes of standards

Following is a list of attributes and criteria for selecting a standard suitable for use by eTRIKS.

Coverage:	The standard addresses the domain with a sufficient number of concepts, term sets and metadata elements to meet the user's needs.
Depth and Breadth:	The standard delivers at an adequate granularity level to address  users needs and describing a study domain with accurate terms.
Relevance/Applicability:	The standard is relevant to the goals of the project, study or data to which it is applied; it meets the intended purpose/use case
Necessity:	The standard identifies elements and concepts which must be described. 
Availability:	The standard is freely available for eTRIKS, academic and non-profit organisations.
Pervasiveness:	The standard is used worldwide and, preferably, across several organizations.
Authority:                	The standard is reliable, verified and accepted, based on a documented vetting procedure, preferably a consensus-based procedure by a standards development organization (SDO).
Quality:	The standard is able to provide enough terms and associated metadata (e.g. name, label, definition, synonyms) . When ontologies are concerned, it means assessing  the nature and accuracy of relationships between terms needs to be assessed.
Readability:                      	The standard is available in human and machine readable formats. Hence, availability of resources if format such as RDF, OWL, SKOS can be used as metric.
Sustainability:                  	The standard is viable and maintained by a recognized community or a sustained organization of good standing.

Note: the order is not an indication of importance.

For each of these facets, evidence will be reviewed and used to assess the suitability of the standard for the purposes of eTRIKS. 

As eTRIKS caters for many different disease areas, it is realised that conflicting influences will arise when selecting standards that cannot be expected to deal equally well with both specific and generic domain representations. The eTRIKS intent is to be practical but the current recommendations are not prescriptive. It is therefore left to data managers to decide on which resources to used and provide all the necessary details.

## 2.3 Versioning of Standards

Standards are artefacts resulting from activities by dedicated bodies, acting in a specific realm to deliver normative documents. This process is often iterative, dealing with use cases depending on pragmatic prioritization and obeying release cycles. It is of paramount important to understand that Standards evolve and adapt to new needs and therefore often undergo alteration, extensions and incremental modifications that warrant the release of updated normative specifications on a regular or ad-hoc basis. Therefore, Standards should always be identified by their name, their version number, the date of the latest release, and, if available, a Unique Resource Identifier (URI). The version of a standard should always be documented in any work utilizing standards for data collection, transport or reporting. In first approximation, clearly identifying the release version of the resource being used is a fundamental requirement. However, versioning could be foreseen at many different levels in particular if incremental updates to a standard exist (such as adding new synonyms to code list). Versioning may occur at the level of synonym sets, at the concept level, and at the level of all data and metadata elements making up a standard. A high level of granularity for versioning is required in validated environments.

## 2.4. Standardization Bodies and Service Providers

Standardization activities are numerous and diverse, taking place in large organizations with industrial strength or at grass root level and academia or both. For historical reasons, many standardization initiatives started from and grew in specific domains of expertise (e.g. proteomics versus transcriptomics, regulatory studies versus research and exploratory studies). This state of affair results in overlapping and competing alternatives, fragmenting standardization efforts, and ultimately impairing integration of multi-type data. 
As eTRIKS mission is to enable and ease integration of multi-type data, eTRIKS will build on the work and expertise of domain standards organizations and build an environment where each data type will be described by an eTRIKS-selected standard(s) (when it/they exist(s)). 

Standards Development Organizations (SDO) that have been considered so far, include: 
W3C
ISO
CDISC
HL7
WHO
OBO foundry

Vocabulary servers
US National Center for Biomedical Ontologies: Bioportal
US National Cancer Institute Enterprise Vocabulary Services: NCI EVS
US Unified Medical Language System: UMLS Terminology Server (requires license agreement and account) 
EMBL-EBI Ontology Lookup Service
Open Knowledge Foundation Linked Open Vocabulary: LOV
CDISC SHARE API (under development): http://www.cdisc.org/cdisc-share

Catalogue of Standards and Resources in Life Sciences:
Biosharing

## 2.4. Gaps in Standards

Two types of gaps in coverage can be found: 
### 2.4.1 Coverage gap in a domain covered by an existing standard
In such a situation, study owners are aware of not only an eTRIKS-approved standard covering the domain of interest, but also a shortage of descriptors and values to accurately annotate their dataset. The central point here is the following: any eTRIKS recommended standard should provide a flexible framework supporting user defined extensions. In CDISC SDTM or SEND standards, the Supplemental Qualifiers special purpose dataset model may be used to capture non-standard variables and their association to parent records in general-observation-class datasets (Events, Findings, Interventions) and Demographics (more on this topic in SDTM Implementation Guide Section 8.4.2). However, those should only be used if no coverage can be achieved by other more precise means available through CDISC domains. So CDISC documentation and training material should be consulted .

### 2.4.2 Coverage gap in a domain not covered by standards
	This is often the case when new technologies emerge, when understanding of the error models is lacking and when field maturity is an issue making it difficult to standardize. The best advice in such a situation is to attempt to recycle existing module, principles in data management. The CDISC SDTM-Implementation Guide describes the overall process for creating a custom domain, which must be based on one of the three SDTM general observation classes. A custom domain may only be created if the data are different in nature and do not fit into an existing published domain.	
Finally, direct contribution to standardization efforts could be made by joining development groups of SDOs or community efforts. When appropriate, a submission of a new CV term may also be logged to the relevant resources. To this end, the tables below supporting this document identify the respective issue trackers associated with each of the semantic artefacts. 

For each, eTRIKS WP3 members will outline procedures intended to guide eTRIKS users in dealing with the situation in a principled manner. The main goal is to ensure request coordination and brokering by eTRIKS members and limit duplication and redundant efforts.

## 2.5 Changes, maintenance and updates to eTRIKS Standard Starter Pack
Science and technology are in constant evolution. As with anything, keeping abreast of those changes will be an essential part of eTRIKS Work Package 3. Therefore, it is essential that readers are aware that recommendations made about which data standards to use may change too. Disruptive technologies, both in the field of wet laboratory hardware but also in the field of computer science, computational biology and information technologies may be introduced and radically alter the way to handle specific data elements.
Conversely, substantial aspects of experimental science are not covered by broadly adopted standards, standards especially in the rapidly growing area of genomics and other -omics.  
Standardization efforts can be slow to bring about actionable documents, meaning that users need to make do with the existing. Alternately, ongoing efforts in specific area are known to exists and their output is announced (for instance, the various working groups in CDISC therapeutic areas publish roadmaps and calendar updates of their progress )
For this reason, eTRIKS Standards Work Package participants will review the changing landscape of data standards and carry out revisions to our recommendations on a regular basis over the course of the eTRIKS project.


<a name="myfootnote14">14</a>: "What Is Provenance - XG Provenance Wiki." 2010. 19 Jun. 2015 (http://www.w3.org/2005/Incubator/prov/wiki/What_Is_Provenance)
