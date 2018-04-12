# Part 3.  Standards in data management

## 3.1 Standards for Data Security, Data Privacy and Compliance with Ethical Guidelines.

While the main focus of the eTRIKS Standards Starter Pack aims at documenting and advising content and annotation standards, the object of the present section is to draw attention to normative guidelines and procedures dedicated to ensure proper handling of clinical data.

### 3.1.1 Data Access and Security 
When it comes to patient and clinical data, the Information Security Standard ISO 27000 family (http://www.iso.org/iso/home/standards/management-standards/iso27001.htm) should be considered as a reference point to establish an industry strength implementation of secured data access and data encryption. The standards specify reliance on two-factor authentication processes for every interaction session with the system. It also specifies appropriate measures for data access logging and audit.

### 3.1.2 Data Privacy and Anonymization
To preserve patient privacy and effectively remove the risk of patient re-identification, data managers must be aware of the latest recommendations for anonymization. Recommendations by BioMedbridges <sup>[29](#myfootnote29)</sup>-<sup>[30](#myfootnote30)</sup>   and eTRIKS WP7  <sup>[31](#myfootnote31)</sup> on ethics should be used as reference documentation.

### 3.1.3 Patient consent and Ethical use of research information.
Whether clinical trial data or electronic health records are involved, it is essential for data managers to clearly identify and document the modalities of recording consent information provided by patients as well as the extent of usage the patients have agreed to. As noted before, there are widespread disparities between countries in Europe and across the world on that topic. One can therefore only refer to current normative documents produced by standardization bodies or regulatories agencies. For the former, the  HL7 V3 Security and Privacy Ontology, Release 1 FHIR<sup>[32](#myfootnote32)</sup> , an effort towards a patient friendly, machine readable  consent description, should be considered. For the latter, the US Food and Drug Administration maintains significant documentation and the 21CFR50.20<sup>[33](#myfootnote33)</sup>  general requirements provide a framework but also the IMI eTRIKS code of practice on secondary use of medical data<sup>[34](#myfootnote34)</sup>  which has been widely adopted in Europe and US.

## 3.2 Principles of good annotation practice

In order to enable within study consistency and ultimately, cross-study queries and/or comparisons and achieve good query recall, many concepts need to be standardized. Those queries can be performed:
- within one given study class, e.g. when querying only clinical trials, or
- across study classes, e.g. when querying clinical and in-vitro studies.

The latter holds most potential for insights or discoveries with relevance to Translational Medicine.  Therefore, we will prioritize our standardization effort on data labels and assays according to the following criteria and order:
a. 	The most commonly used data labels and their associated textual content across studies, such as (this is not an exclusive list): study protocol elements, study design, demographics, species, strains, organs/body parts, tissues/ primary cells, cell lines, virus, chemicals, peptides/proteins, RNAs (all kinds), genes, DNA variations, DNA modifications, vital signs, behavioral signs, structures/forms/colors, diseases, adverse events, interventions, medical history etc...

b. The data labels and their associated content (qualitative or quantitative values) of the most commonly used assays across studies, such as laboratory testing, gene expression microarray, RNA seq, SNP microarray, DNASeq.

c.  In a given project, the project-specific _(those less commonly used)_ data labels and assays will be standardized according to the project time lines, following the basic procedure outlined earlier in the document.
The use of standards relies on the principles and basic rules of good annotation practice that are:
1. All the concepts (i.e. data labels and text content) are described by a _Controlled Vocabulary Term (CVT)_ in-lieu of free-text. Concepts from legacy studies, medical comments, and observation notes are not replaced by CVTs but mapped to CVTs (principle of data provenance).
2. A CVT has a unique identifier issued by the associated authority responsible for maintaining the term.
3. Numerical values are converted in the International System (SI) of units<sup>[35](#myfootnote35)</sup>  while retaining the original values (principle of data provenance).
4. Derived data are collected with their primary data and algorithm or methodology used for the data derivation (principle of data provenance).
5. All measurements and observations obey to the principle of data provenance and are associated with the following concepts that answer the What, the Who, the When, the Where, the How and the Why:
    - What organization and/or individual perform them?
    - In what study class have they been performed?
    - For clinical studies, at what study activity identifier (ID) have they been performed?
    - Where (i.e. geographic location) have they been performed? 
    - From what subject ID have they been performed?
    - From what specimen ID or part of the subject have they been performed?
    - When have they been performed or when has the specimen been collected (local time)?
    - What is measured or observed?
    - What assay has been used?
    - What biological material has been used by the assay? RNA, DNA, protein, serum etc…?

#### Example and Application: Procedure for selecting relevant standards given an eTRIKS dataset


Before starting the standard selection, the study owners have to define the investigation scope, the study(ies), the assays, and the variables that will be recorded in the eTRIKS platform.  If several studies are recorded, then the workflow is used separately for each study.
The following steps guide a curator towards choosing the most suitable protocol / reporting / semantic /exchange standards for a study.
The workflow steps should be followed in the below described order.
A.     Reporting standards
B.     Vocabulary standards and standardized units
C.     Exchange standards
 
## 3.3 Prospective data capture
Standards should be considered at the time of protocol and study design. Where possible data should be collected according to the chosen standards at the time of data generation and capture. To this end, eTRIKS WP3 starter pack recommends study data managers to create a ‘data management plan’ following the guidelines which will be described in a series of “operational documents” and as now mandated by IMI2 and H2020 programs<sup>[36](#myfootnote36)</sup> . 

## 3.4 Retrospective data capture and legacy data
Legacy data may be re-curated to conform to a given standard by the data curators. However, original data are always kept and mapped to Controlled Vocabulary Terms (CVT).
In either situation, dealing with retrospective or prospective data, a data validation plan (DVP) should be established prior to performing any modification on the submitted data. eTRIKS WP3 is currently working at creating specific documentation about this particular step.

## 3.5 Case study
One of the eTRIKS objectives is to show how and why the adoption and use of standards can benefit the downstream knowledge generation within and across projects. Initial experience gained from the U-BIOPRED project<sup>[37](#myfootnote37)</sup>  will be reported in another document.




---------------

<a name="myfootnote15">15</a>:  "World Wide Web Consortium (W3C)." 19 Jun. 2015 (http://www.w3.org/)

<a name="myfootnote28">28</a>: "Coalition For Accelerating Standards and Therapies (CFAST)." 9 Jun. 2015 (http://blogs.fda.gov/fdavoice/index.php/tag/coalition-for-accelerating-standards-and-therapies-cfast/)

<a name="myfootnote29">29</a>:  Sariyar, M. "Sharing and Reuse of Sensitive Data and Samples ..." 2015. (http://www.ncbi.nlm.nih.gov/pubmed/26186169)

<a name="myfootnote30">30</a>: "Supporting researchers sharing sensitive data: identifying ..." 2016. 11 Mar. 2016 (https://www.biomedbridges.eu/supporting-researchers-sharing-sensitive-data-identifying-requirements)

<a name="myfootnote31">31</a>: Bahr, A. "Code of practice on secondary use of medical data in ..." 2015. (http://idpl.oxfordjournals.org/content/early/2015/09/19/idpl.ipv018.abstract)

<a name="myfootnote32">32</a>: "HL7 Version 3 Standard: Security and Privacy Ontology ..." 2014. 10 Mar. 2016 (http://www.hl7.org/implement/standards/product_brief.cfm?product_id=348)

<a name="myfootnote33">33</a>: "Search for FDA Guidance Documents > A Guide to Informed ..." 2009. 6 Mar. 2016 (http://www.fda.gov/RegulatoryInformation/Guidances/ucm126431.htm)

<a name="myfootnote34">34</a>: "Code of Practice  eTRIKS." 2015. 10 Mar. 2016 (https://www.etriks.org/code-of-practice/)

<a name="myfootnote35">35</a>: Bureau International des Poids et Mesures, Commission électrotechnique internationale, and Organisation internationale de normalisation. Guide to the Expression of Uncertainty in Measurement. International Organization for Standardization, 1995
<a name="myfootnote36">36</a>: "Guidelines on Data Management in Horizon 2020." 2016. 14 Mar. 2016 (https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf)
<a name="myfootnote37">37</a>:  Bel, EH et al. "Unbiased Biomarkers for the Prediction of Respiratory Disease Outcome (U-BIOPRED) Consortium, Consensus Generation. Diagnosis and definition of severe refractory asthma: an international consensus statement from the Innovative Medicine Initiative (IMI)." Thorax 66.10 (2011): 910-7.




