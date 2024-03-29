# Appendix

## A.I. Glossary (terms and definitions)

### Organizations and Consortia
  -	 eTRIKS refers to the eTRIKS consortium.
  -	CDISC stands for Clinical Data Interchange Standards Consortium.
  -	TCGA stands for The Cancer Genome Atlas<sup>[44](#myfootnote44)</sup> .
  -	SI units refer to the International System (SI) of units
  -	tranSMART Foundation (www.transmartfoundation.org) is an organization looking after the tranSMART software.

### Person and Organization Roles
  -	A study owner is the legal person (natural or judicial) who is responsible for authorizing the access and/or the use of data from a study.
  -	A collaborator is a study owner who 1) gives the right of handling the data of a study to eTRIKS, and 2) follows eTRIKS guidelines, where applicable.

### Data Curation
  -	_Data curator_ is someone who performs data curation, namely a group of management activities required to ensure long-term research data preservation such that data are available for reuse and evaluation. These management activities consist in harmonizing annotation, cleaning, converting, standardizing, and formatting data to ensure consistency, increase recall and enable cross study comparison.
  -	Curated data are data for which the values, the labels, the formats, and the provenances follow the curation rules and conventions defined by eTRIKS.

### Data Labels and Controlled Terms
  -	_Data labels_ (also called variables in data management) are descriptions of data (often names; in a table they are column headers)
  -	_Data Dictionary_ is a flat list of terms whose labels and definitions are agreed upon
  -	_Controlled Terminology_ is a tree of terms whose labels and definitions are agreed upon and which are organized in a hierarchical structure.
  -	_A Reference Ontology_ is a semantic resource developed to represent formally a domain of Science, defining entities, their properties and relation with respect to other entities. The Gene Ontology<sup>[45](#myfootnote45)</sup> is a reference ontology for defining gene function, molecular process and biological component while Human Phenotype Ontology<sup>[46](#myfootnote46)</sup> is a reference ontology for the description of human disorders.
  -	_An Application Ontology_ is a semantic resource developed specifically to answer uses cases and specific tasks defined by a focused software application such as user interface. Application Ontology often combines controlled vocabulary terms from various ‘reference’ resources (i.e. reference ontologies) by mixing and matching in an ad-hoc fashion (in the worst of cases), or according to principled way (for instances by combining reference ontologies sharing the same development practices). Application Ontologies requires constant synchronization with Parents/Source artefacts, something which can be achieved through software agents but places infrastructure demands. EFO, The experimental Factor Ontology<sup>[47](#myfootnote47)</sup>, is an application ontology specifically developed for EMBL-EBI ArrayExpress needs.
  -	_A Controlled Vocabulary Term (CVT)_ is a term that belongs to a terminology, a dictionary, or an ontology for which an authoritative textual definition exists (complemented by a formal definition for ontologies). 
  -	_An eTRIKS Controlled Vocabulary Term  (eCVT)_ is a unique CVT in the eTRIKS CVT library, and has a corresponding identifier and the associated standard source.
    - The _eCVT library_ contains all the eCVT used by eTRIKS in eTRIKS.
    - _eTRIKS data labels_ are eCVT.
  -	_Standardized data_ are either eCVT or numerical values converted to International System (SI) of units.

### Data Types and Levels
  -	_Metadata_ provide descriptive and provenance information about data.
  -	_Primary data_ (Level 1 Data according to The Cancer Genome Atlas (TCGA) classification (https://tcga-data.nci.nih.gov/tcga/tcgaDataType.jsp, also known as “raw data”) are assay results that have not been processed/transformed, and are either measurements or observations.
  -	_Derived data_ (Level 2 Data according to TCGA classification) are data that are calculated from, or given according to, several primary or derived data. Treatment responses are derived data: they are assigned according to primary data.
    - Example 1.	A treated patient with a tumor size (primary data) above an arbitrary threshold is considered as “non-responder” (derived data).
    - Example 2.	Ages are derived data calculated from the birth and study starting dates (primary data).
  -	_Interpreted data_ (Level 3 Data according to TCGA classification) are data that result from the interpretation of Level 1 or 2 Data by using reference data.
    - Example. 	In a microarray, normalized intensity values associated with a probe set IDs are level 2 data, while the gene names associated with the probe set IDs are level 3 data.
  -	_Reference data_ provide information from biological databases and resources (e.g. gene annotation of a microarray probe set; SNP location in the genome and their mapping to genes).

### Investigation, Study and Observations, Assays and Measurements 
  -	A study is a central unit containing information on subjects under study and its characteristics. A study has associated assays.
  -	A study class is defined according to the nature (type) of subjects (i.e. human, non-human animal, cell, virus) under study. 
    -	A clinical study is a type of study where study subjects are human subjects  
    	-	A preclinical study is a type of study where study subjects are animals, tissues,  or cells.
  -	An investigation or project is a collection of related studies.
  -	A subject is the living entity or organism under study, and can be a human, a non-human animal, a cell, or a virus
  -	An assay is a measurement process performed either on a subject or on material derived from the subject. Assay results are findings.
    -	Measurements are quantitative data of an assay and have a numerical value.
    -	Observations are qualitative data of an assay result, and do not have a numerical value.
  -	An image is an observation, while its signal levels are measurements.
  -	An ‘omic’ assay is a molecular biology techniques that enables simultaneous measurement of a large collection of molecular entities (transcripts, protein, small molecules). An ‘omic’ profiling may be “targeted” (meaning a limited number of known entities are assayed, such as in ELISA, Luminex or RT-PCR multiplex panel) or may be “untargeted” (meaning any entity in a given molecular class may be measured (such as in pan-genome microarrays, RNA-Seq)


### TranSMART:
  -	_TranSMART (TM)_ is the data warehouse that eTRIKS will contribute to develop in order to enable data hosting, sustainability, visualization and analysis.
    -	A tranSMART concept tree refers to the overall organisation and representation of the study concepts in the TranSMART User Interface (UI) (see an example of a tranSMART concept tree in Annex III).


## A.II. eTRIKS Standards as available from BioSharing:

Biosharing (www.biosharing.org) is an open source initiative aiming at providing an up-to-date overview of the standards landscape in the life science. Besides various advanced search and filtering features, the registry offers communities to present the set of resources they rely on for their data management needs. The following figure illustrates how eTRIKS may use the Biosharing website to further broadcast and publicize technical recommendations.

![alt text][image B]

Figure 1. The eTRIKS view of relevant standards as available from Biosharing website.
https://www.biosharing.org/collection/5?q=&view=table


## A.III. tranSMART master tree

![alt text][image C]

Left pane: First pass of a recommended hierarchy to use for tranSMART data explorer 
Right pane: 2 views of a CDISC SDTM based TransMART master tree data explorer.  The lower pane expands the ‘CDISC STDM Adverse Event Domain showing possible descriptors used in the CDISC Tabulation format.

-----------------
<sup>
<a name="myfootnote44">44</a>: "Home - The Cancer Genome Atlas - Cancer Genome - TCGA." 2005. 8 Jun. 2015 (http://cancergenome.nih.gov/)

<a name="myfootnote45">45</a>: "Gene Ontology Consortium." 2002. 8 Jun. 2015 (http://geneontology.org/)

<a name="myfootnote46">46</a>: "The Human Phenotype Ontology." 2008. 8 Jun. 2015 (http://www.human-phenotype-ontology.org/)

<a name="myfootnote47">47</a>: "Experimental Factor Ontology - EMBL-EBI." 2009. 8 Jun. 2015 (http://www.ebi.ac.uk/efo)
</sup>

----------------
[image B]: https://github.com/proccaserra/eTRIKS-SSP/blob/master/figures/eSSP-FAIRsharing.png "image B"
[image C]: https://github.com/proccaserra/eTRIKS-SSP/blob/master/figures/eSSP-TransMART-MasterTree.png "image C"