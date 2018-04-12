# Part 4.  eTRIKS recommended resources

This section points to dedicated and specific documents and specifications that detail further eTRIKS recommendations as to which standards may be used in Data Management Plans (for instance, as described in H2020 data management document) 

## 4.1 eTRIKS - Recommendations for Exchange Format for Clinical Study

### 4.1.1 CDISC Standards
The CDISC suite of data standards have been designed to support various stages of the clinical research process while conforming to common research business processes and regulatory guidelines. Taken collectively, CDISC standards can streamline the medical research process, saving time and cost while improving quality. Use of data standards can increase the value and reusability of data while preserving meaning as data passes through various stages of the research process. The use of CDISC standards at project initiation has been found to save 70 - 90% of time and resources spent prior to first patient enrolled and approximately 75% of the non-patient participation time during the Study Conduct and Analysis stages . CDISC standards reap substantial benefits, qualitative and quantitative, during the entire research process for all types of research studies including academic, nutritional, device, outcomes and regulated research. Standards reduce complexity and generate a coherent data space. 

|CDISC Standards	|Uses/Value   	|Application   	|
|---	|---	|---	|
|Protocol Representation Model (PRM), Study Design Model (SDM) http://www.cdisc.org/protocol The PRM toolkit gives 30 basic concepts essential for all protocols and is more easily understandable than the full UML model.	| The Protocol Representation Model (PRM) is a BRIDG-based model and tools for representing standard clinical research protocol elements and relationships. The Study Design Model (SDM-XML) is an XML schema specification based on the Operational Data Model (ODM) for representing clinical study design, including structure, workflow and timing. PRM supports the interchange (re-use) of information standard to medical/clinical research protocols of any type.  V1.0 supports study tracking and clinical trial registration (CTR) in clinicaltrials.gov, WHO or EudraCT; study design (arms, elements, epochs) and scheduled activities; eligibility criteria.  In Unified Model Language (UML) format as a subset of BRIDG – spreadsheet and templates to ease use are in progress. A common problem with the typical protocol document is that it is not in a useful format for information management and reuse. The PRM is the foundation for a machine readable protocol with such ‘re-use’ being one of the advantages as well as visibility and  comprehensibility of the study design. Clinical Trial data managers should primarily be concerned with obtaining study protocol in such format. When making cross project data comparisons, this summary information is the best way to understand the objectives of and background to the data collection. It enables to categorize studies, to make cross comparisons by identifying like data and the relationships between different datasets. When machine readable protocol representation is absent,  one should be built by the data manager following the proposed standard representation. The PRM gives the added clinical research benefits of:  - Increasing transparency of clinical research,  - Adhering to study registry requirements,  - Sending information to Ethics Committees,   - Writing post study clinical reports,   - Submission of trial summary info to regulators,   - Machine readable search elements,   - Avoid poor study designs and further costs and/or study re-runs.	|Planning   	|
|Clinical Data Acquisition Standards Harmonization (CDASH) http://www.cdisc.org/cdash |Clinical Data Acquisition Standards Harmonization is a specification data collection domains and variables for Case Report Form (CRF) data with standard question text, implementation guidelines, and best practices.   	|Planning/Data Collection   	|
|Laboratory Data Model (LAB) http://www.cdisc.org/lab 	|Specification describing standard content for the acquisition and interchange of clinical laboratory data between central labs and sponsors or contract research organizations (CROs). Vocabulary standard that facilitates exchange of clinical trial laboratory data between central laboratories and study sponsors, CROs or EDC vendors.    	|Planning/Data Collection 	|
|Study Data Tabulation Model (SDTM) http://www.cdisc.org/sdtm   	|Study Data Tabulation Model (SDTM) is the general model for representing study tabulation data used in clinical research. The SDTM Implementation Guide (IG) describes domains and variables for data from Human Clinical Trials for Drug Products and Biologics. SDTM is the standard for data tabulations from CRF data from multiple sites for a clinical study; it is the preferred method for providing data to the FDA for regulatory review. Collecting data in CDASH format can eliminate the need to map data to SDTM at the end of the clinical study process. Efficacy domains are in progress and are defined in the SDTM IG, as well as many described and available in the related Therapeutic Area User Guides.  SDTM model and its implementation guidelines 3.2 highlight new specific finding domains: extensions for microbiology specimen, microbiology susceptibility and pharmacogenomics data.   	|Data Tabulation / Preparation to Preservation (and Regulatory Submission if needed)   	|
|Analysis Dataset Model (ADaM)   	|Analysis Data Model describes fundamental principles and standards for representing analysis datasets and metadata to support statistical analysis and also statistical regulatory reviews. It is the preferred method by FDA statistical reviewers for submitting research data. The ADaM Implementation Guide (IG) describes standard data structures, conventions and variables used with ADaM. A vocabulary standard for analysis datasets to support statistical analysis and also statistical regulatory reviews; preferred method for providing data for review by FDA statistical reviewers.   	| Data Tabulation / Preparation to Preservation (and Regulatory Submission if needed  	|
|Define-XML  http://www.cdisc.org/define-xml 	|The XML-based (ODM-based) standard referenced by FDA as the specification for the data definitions for CDISC SDTM, SEND and ADaM datasets and the current mechanism for providing eSubmissions metadata to FDA.   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
|Study Design in XML http://www.cdisc.org/study-trial-design  	|The CDISC Study Design Model in XML (SDM-XML) version 1.0 allows organizations to provide rigorous, machine-readable, interchangeable descriptions of the designs of their clinical studies, including treatment plans, eligibility and times and events. As an extension to the existing CDISC Operational Data Model (ODM) specification, SDM-XML affords implementers the ease of leveraging existing ODM concepts and re-using existing ODM definitions. SDM-XML defines three key sub-modules – Structure, Workflow, and Timing – permitting various levels of detail in any representation of a clinical study design, while allowing a high degree of authoring flexibility   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
|Dataset-XML http://www.cdisc.org/dataset-xml    	|Dataset-XML, released for comment under the name “StudyDataSet-XML”, and renamed to avoid confusion with the CDISC SDS team, is a new standard used to exchange study datasets in an XML format. Dataset-XML supports the interchange of tabular data for clinical research applications using ODM-based XML technologies. The Dataset-XML model is based on the CDISC Operational Data Model (ODM) standard and should follow the metadata structure defined in the CDISC Define-XML standard.   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
|---	|---	|---	|
| **Semantics** 	|   	|   	|
| Controlled Terminology http://www.cdisc.org/terminology 	|The controlled standard vocabulary and code sets for all of the CDISC models/standards; maintained openly and freely by NCI Enterprise Vocabulary Services (EVS: http://evs.nci.nih.gov/)).   	|Annotation   	|
| Glossary  http://www.cdisc.org/cdisc-glossary	|Glossary with definitions of acronyms and terms commonly used in clinical research.  Abbreviations and Acronyms also included.   	|Annotation   	|
| Biomedical Research Integrated Domain Group (BRIDG) Model http://www.cdisc.org/bridg 	|Biomedical Research Integrated Domain Group (BRIDG) UML model of the semantics of protocol-driven clinical research.   	|Annotation   	|
| Clinical Outcome Assessment Instruments (Questionnaires) http://www.cdisc.org/ft-and-qt	|SDTM Implementation Guide Supplements with annotated CRFs and Controlled Terminology for representing data from Clinical Outcome Assessments (COAs), Questionnaires, and Functional Tests commonly used in clinical studies.   	|Annotation   	|
|---	|---	|---	|
| **Specialty Area Standards** 	|   	|   	|
|---	|---	|---	|
| Therapeutic Area (TA) Standards 	|Various standards are now being developed to augment the basic CDISC standards that support safety data across essentially any protocol. These new standards are focused on specialty areas to support efficacy data (e.g. Alzheimer’s and Parkinson’s Diseases, Cardiovascular Disease, Diabetes, Tuberculosis) and also Imaging and Devices.   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
| Medical Devices http://www.cdisc.org/devices 	|The Study Data Tabulation Model Guide for Medical Devices (SDTMIG-MD) v.1.0 defines recommended standards for the submission of data from clinical trials in which medical devices are used. The document includes seven new domains, developed by a team comprised of medical device experts, CDISC experts, and the FDA (CDRH and CBER), and represents years of work by the members of the CDISC Medical Device team. Training on these seven new domains has been incorporated into the standard SDTM training available through CDISC   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
| Pharmacogenomics/Genetics (PGx) http://www.cdisc.org/pharmacogenomics-genetics	|Version 1.0 Provisional of the SDTM Implementation Guide:  Pharmacogenomics/Genetics (SDTMIG-PGx), published 2015-06-01, describes standards to guide the organization, structure and format of gene-related tabulation datasets submitted as part of a product application to a regulatory agency. SDTMIG-PGx is being released for provisional use, since it introduces new variables and constructs that will be added to the forthcoming SDTM v1.5, and to allow operational testing and evaluation of this new standard by the CDISC user community.   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
| Specialty Areas http://www.cdisc.org/specialty-areas 	| Solution Kits for Specialty Areas describe how to use CDISC Foundational Standards to represent content for specific types of trials or certain broad categories of data.  For example, the SDTM Implementation Guides for Medical Devices and Pharmacogenomics/Genetics both began as new specialty area projects before being formally released as independent standards.  Some of these specialty areas are very similar to therapeutic area data standards, but they are not governed under the CFAST initiative so are currently listed separately (though in some cases them may evolve into CFAST projects at a later date.   	|Preparation to Preservation (and Regulatory Submission if needed)   	|
| Questionnaires, Ratings and Scales (QRS) http://www.cdisc.org/qrs | Questionnaires are named, stand-alone measures designed to provide an assessment of a concept.  Questionnaires have a defined standard structure, format, and content; consist of conceptually related items that are typically scored; and have documented methods for administration and analysis.  Questionnaires consist of defined questions with a defined set of potential answers.  Most often, questionnaires have as their primary purpose the generation of a quantitative statistic to assess a qualitative concept. CDISC publishes standard Questionnaires, Ratings and Scales (QRS) products, which include SDTM Annotated CRFs and Supplements to the SDTMIG along with the related controlled terminology.    	|Preparation to Preservation (and Regulatory Submission if needed)   	|   	



### 4.1.2 SPREC Guidelines for Solid and Fluid Samples:
In the context of clinical trial, it is critical to keep in mind issues related to human tissue and sample preservation and how preanalytical handling of the samples can impact the quality of biological signal derived from samples in downstream workflows. Therefore, eTRIKS WP3 needs to highlight the Standard Preanalytical Coding for Biospecimens: Review and implementation of the Sample PREanalytical Code (SPREC) guidelines produced by the International Society for Biological and Environmental Repositories (ISBER). 
The guidelines, which start to gain momentum in the biobanking initiatives, define a coding system allowing for compact reporting of key collection, preanalytical processing, preservation and storage conditions for solid and fluid biological samples.



## 4.2 eTRIKS - Recommendations for Exchange Format for Non-Clinical Studies (Animal and in-vitro Studies)

### 4.2.1 CDISC Standards for non-clinical studies


|CDISC Standards	|Uses/Value   	|
|---	|---	|
|Laboratory Data Model (LAB) http://www.cdisc.org/lab	|Vocabulary standard that facilitates exchange of clinical trial laboratory data between central laboratories and study sponsors, CROs or EDC vendors. The LAB model has an extension for microbiology and extensions for pharmacogenomics data.   	|
|Standard for the Exchange of non-Clinical Data (SEND) http://www.cdisc.org/send	|An extension of SDTM specifically developed for preclinical or non-clinical studies, e.g. toxicology.  	|
|Controlled Terminology http://www.cdisc.org/terminology	|The controlled standard vocabulary and code sets for all of the CDISC models/standards; maintained openly and freely by NCI Enterprise Vocabulary Services (EVS).  	|
|Glossary http://www.cdisc.org/cdisc-glossary 	|The CDISC dictionary of terms and their definitions related to the CDISC mission. Abbreviations and Acronyms also included.   	|


### 4.2.2 Non-Regulatory Standards for Research  Studies


|CDISC Standards	|Uses/Value   	|
|---	|---	|
|Investigation Study Assay http://.isatab.sf.net 		|‘Investigation’ (the overall project context which may group several studies), ‘Study’ (a defined research experiment why may use several different types of assays) and ‘Assay’ (sets of data acquisition events) Tabular format is a meta-format, built purposefully to  manage diverse set of life science, environmental and biomedical experiments employing one or a combination of functional genomics technologies while ensuring data deposition to various key omic data repositories.   	|
|Primary Data Format for Omics	|The following link provides a complete overview of the existing format specifications available to support individual ‘omic like type of data. Section 4.5 eTRIKS-WP3-Standard-Starter-Pack-Recommandations-Exchange-Format-for-Omics	|


## 4.3 eTRIKS - WP3 - Standard Starter Pack Recommendations for Database Resource Identification

### 4.3.1 Resource Identification:
This is an integral part of the recommendations. Free text should be limited whenever possible and controlled metadata elements should be supplied instead, alongside with their  associated identifier, the associated authority issuing it, without forgetting indicating the version of the database or semantic resource used.
The following section and specific documents will identify resources eTRIKS encourages submitters to rely on when preparing their submission in the case of retrospectives studies, or when planning data collection in the case of prospective studies.
If the submitters elect to follow eTRIKS advice, they will facilitate the curation tasks and speed up loading in the relevant tool while reducing operational cost. Should the submitters favour relying on resources outside those specified by eTRIKS, adherence to the resource identification requirements will be of help, leading to easier and more efficient mapping as eTRIKS curation team will be able to take advantage of mapping resources. 

Free text terms can not be entirely avoided but controlled terminologies should always be prefered as used more efficiently by search and indexing software agents.  In the absence of reliable or affordable natural language processing tools, enforcing controlled terms is a step to facilitate data integration.

#### 4.3.1.1 Identification of Molecular Entities when reporting ‘omics’ data

The following resources are recommended for tagging or linking entities of interest to database records. eTRIKS recommends using those resources and curation may be applied to align submission on those recommendations. We remind here that the purpose is to ensure annotation consistency, improve query recall and facilitate translational research use cases.


| Molecular Entity  	|Resource Name   	|Biosharing identifier   	|Resource URI   	|Resource Identifier pattern   	|Comment   	|
|---	|---	|---	|---	|---	|---	|
|**Small Molecules**   	|   	|   	|   	|   	|   	|
|Metabolites   	|Pubchem   	|biodbcore-000455   	|http://pubchem.ncbi.nlm.nih.gov/summary/summary.cgi?cid=$id   	|$id=^\d+$   	|   	|
|   	|CHEBI   	|bsg-000039   	|http://www.ebi.ac.uk/chebi/searchId.do?chebiId=$id   	|$id=^CHEBI:\d+$   	|   	|
|Lipids   	|Lipid Maps   	|biodbcore-000559   	|http://www.lipidmaps.org/data/get_lm_lipids_dbgif.php?LM_ID=$id   	|$id=^LM(FA|GL|GP|SP|ST|PR|SL|PK)[0-9]{4}([0-9a-zA-Z]{4,6})?$   	|   	|
|Drugs   	|DrugBank   	|biodbcore-000304   	|http://www.drugbank.ca/drugs/$id   	|$id=^DB\d{5}$   	|   	|
|   	|WHOdrug (*)   	|Not available   	|http://www.umc-products.com/DynPage.aspx?id=73588&mn1=1107&mn2=1139   	|   	|(*)WHOdrug is not freely available and its cost can be a major limitation for academic institutions.   	|
|**Biopolymer**   	|   	|   	|   	|   	|   	|
|DNA   	|ensEMBL gene   	|biodbcore-000330   	|http://www.ensembl.org/   	|$id=ENSG\d+$   	|   	|
|   	|Entrez Gene (aka NCBI Gene)   	|biodbcore-000449   	|http://www.ncbi.nlm.nih.gov/gene/$id   	|$id=^\d+$   	|   	|
|messenger RNA   	|ensEMBL transcript   	|biodbcore-000330   	|http://www.ensembl.org/   	|$id=ENST\d+$   	|   	|
|microRNA   	|mirbase   	|biodbcore-000569   	|http://www.mirbase.org/cgi-bin/mirna_entry.pl?acc=$id   	|$id=MI\d{7}   	|   	|
|Protein   	|Uniprot   	|biodbcore-000544   	|http://www.uniprot.org   	|$id=^([A-N,R-Z][0-9]([A-Z][A-Z, 0-9][A-Z, 0-9][0-9]){1,2})|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])(\.\d+)?$   	|   	|
|DNA variant (**)   	|   	|   	|   	|   	|   	|
|SNP   	|NCBI dbSNP   	|biodbcore-000438   	|http://www.ncbi.nlm.nih.gov/projects/SNP/snp_ref.cgi?rs=$id   	|$id=^rs\d+$   	|Human Genome Variation Guidelines for annotation and nomenclature  (http://www.hgvs.org/mutnomen/) (used by CDISC PGX extension)   	|
|Structural Variation   	|NCBI ClinVar   	|biodbcore-000739   	|http://www.ncbi.nlm.nih.gov/clinvar/   	|   	|Human Genome Variation Guidelines for annotation and nomenclature  (http://www.hgvs.org/mutnomen/) (used by CDISC PGX extension)   	|


(NOTE) Consider Locus Reference Genomic (LRG)-sequences now or in the future (more information at: http://www.lrg-sequence.org/faq#faq_1)



#### 4.3.1.2 Important Reagent Resources

The table below lists major resources to be aware of when describing in-vitro based work. eTRIKS standard working group is aware of ongoing initiatives (e.g. cell line registry) and new versions of the eTRIKS Standard Starter Pack will reflect progress accordingly.

|Molecular Entity   	|Resource Name   	|Biosharing identifier   	|Resource URI   	|Resource Identifier pattern  	|
|---	|---	|---	|---	|---  	|
|antibodies   	|antibody-registry  	|biodbcore-000182   	|http://antibodyregistry.org/AB_$id   	|$id=^\d+{6}$  	|
|Plasmids and vectors   	|addgene   	|biodbcore-000196   	|www.addgene.org/$id   	|$id=^’\d+$  	|
|cell lines   	|ATCC   	|biodbcore-000210   	|http://www.lgcstandards-atcc.org/Products/All/$id.aspx    	|$id=^’\d+$  	|



#### 4.3.1.3 Important Resources for Describing Medical Devices

In March 2016, the United States Foods and Drug Administration, in collaboration with the US National Library of Medicine released the ‘accessGUDID’ database of medical devices, with the aim of providing a consistent and standard way to identify medical devices throughout their distribution and use by health care providers and patients.



|Entity   	|Resource Name   	|Biosharing identifier   	|Resource URI   	|Resource Identifier pattern  	|
|---	|---	|---	|---	|---  	|
|Medical Device   	|GUDID  	|[biodbcore-000748](https://biosharing.org/biodbcore-000748)  	|https://accessgudid.nlm.nih.gov/devices/search?query=$id  	|$id=^\d+{14}$ 	|

