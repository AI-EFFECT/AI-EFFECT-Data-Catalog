







Artificial Intelligence Experimentation Facility For the Energy sector





D6.2: Data Management Plan	










Document Information
DOCUMENT/DELIVERABLE ID	D6.2
TYPE	Report
DISTRIBUTION LEVEL	Public
DUE DELIVERY DATE	31.03.2025
DATE OF DELIVERY	 
VERSION	V1.0
DELIVERABLE RESPONSIBLE	EEU
AUTHORS	 Joep van Genuchten (EEU)
Gianluca Lipari (EEU)
OFFICIAL REVIEWERS	 

Document History
VERSIONS	AUTHORS	DATE	CONTENT AND CHANGES
V0.1	Joep van Genuchten	03.03.2025	First Draft
V0.2	Gianluca Lipari	12.03.2025	First Draft Review
V0.3			Revision
 V1			Final Version


Contents
Executive Summary	6
Abbreviations and Acronyms	7
1	Introduction	8
1.1	Objectives of the work reported in this deliverable	8
1.2	How to read this document	8
2	Methodology	9
2.1	FAIR principles	9
2.2	Data classification scheme	9
2.2.1	Open Information	9
2.2.2	Internal Information	9
2.2.3	Restricted Information	9
2.2.4	Personal Information	10
2.2.5	AI Generated Information	10
2.2.6	Conclusion	10
2.3	Data Governance Roles	10
3	Data Management Plan	11
3.1	Open Information	11
3.1.1	Findable	11
3.1.2	Accessible	11
3.1.3	Interoperable	11
3.1.4	Reusable	11
3.2	Internal Information	12
3.2.1	Findable	12
3.2.2	Accessible	12
3.2.3	Interoperable	12
3.2.4	Reusable	12
3.3	Restricted information	12
3.3.1	Findable	12
3.3.2	Accessible	13
3.3.3	Interoperable	13
3.3.4	Reusable	13
3.4	Personal Information	13
3.4.1	Findable	13
3.4.2	Accessible	13
3.4.3	Interoperable	14
3.4.4	Reusable	14
3.5	AI generated information	14
3.5.1	AI for reporting	14
3.5.2	Using AI	14
3.5.3	Creating AI	15
4	Data summary	15
4.1	UC1: Multi Energy and Sector Coupling	15
4.2	Regulatory Compliance Strategy for UC1	16
4.2.1	AI System for UC1	16
4.2.2	Training Data Collection and Processing Procedures for UC1	16
4.2.3	Test and Validation Procedures for UC1	16
4.2.4	Prompt Response Log for UC1	17
4.2.5	Training data set for UC1	17
4.2.6	Validation data set	17
4.3	UC2: Transmission Congestion Management	18
4.3.1	Regulatory Compliance Strategy for UC2	18
4.3.2	Validation data set for UC2	18
4.3.3	Training Data Collection and Processing Procedures for UC2	18
4.3.4	Prompt Response Log for UC2	18
4.3.5	Test and Validation Procedures for UC2	19
4.3.6	AI System for UC2	19
4.3.7	Training data set for UC2	19
4.4	Energy efficiency, management and sharing for local energy communities	20
4.4.1	Test and Validation Procedures for UC4	20
4.4.2	Training data set for UC4	20
4.4.3	Regulatory Compliance Strategy for UC4	20
4.4.4	Prompt Response Log	20
4.4.5	Training Data Collection and Processing Procedures for UC4	21
4.4.6	Validation data set for UC4	21
4.4.7	AI System for UC4	21
4.5	DER integration into Distribution Systems	22
4.5.1	Regulatory Compliance Strategy for UC3	22
4.5.2	Training data set for UC3	22
4.5.3	Validation data set for UC3	22
4.5.4	Prompt Response Log for UC3	22
4.5.5	AI System for UC3	23
4.5.6	Training Data Collection and Processing Procedures for UC3	23
4.5.7	Test and Validation Procedures for UC3	23


Executive Summary
This deliverable describes the identified data categories used within the AI-EFFECT project by the different project partners as well as ethical aspects and data handling requirements. For the description of the data categories, each data set is broken down into the type of data and it is explained for what purpose the data is collected or generated. The source of the data is evaluated, and the confidentiality assigned. For cases of publishing project outcomes, for instance data sets, also the usefulness to external parties is explained and if already known repository named. At this stage of planning, however, not more details are available. For ethical data handling and collection, relevant local, national, and international regulations, laws and agreements must be investigated and observed. This document is the first step to develop plans to obtain and document the informed consent of stakeholders regarding the use of their personal data. With these points in mind, the AI-EFFECT project is carefully considering how it will handle any personal data used during the project. At the date of writing this report, all work packages are either at an early phase in the planning of their data requirements or have not started their work yet. Detailed planning of the data use aspects will be undertaken during the first year of the project and the monitoring of the ethical use of the field trial data will continue during the project lifetime. Therefore, an updated version of this deliverable will be released in project month 18.

Abbreviations and Acronyms
	Abbreviations and Acronyms
CSV	Comma-Separated Values
DMP	Data management plan
DoA	Description of Action
EC	European Commission
EU	European Union
FAIR	Findable, accessible, interoperable, re-usable
GDPR	General Data Protection Regulation
ORDP	Open Research Data Pilot
R&D	Research and Development
IDS-RAM	International Data Spaces Reference Architecture Model

1 Introduction
Data management is an important task in every research project. Since Horizon 2020 and continuing with Horizon Europe programmes, European projects are required to adhere to the Open Research Data Pilot (ORDP). There are two main pillars to the Pilot: developing a Data Management Plan (DMP) and providing open Research Data Pilot Access to research data, if possible. The AI-EFFECT project will, as much as possible, comply with the ORDP requirements by creating and updating a project’s Data Management Plan, initiated with this document, and by pledging to publish scientific information according to the FAIR principle in publicly accessible research data repositories whenever possible. The FAIR principle is explained in detail in section 2.1. The AI-EFFECT project will identify best practices for a DMP following the work of previous H2020 and Horizon Europe projects. This is the second revision of the Data Management Plan (DMP). We will present a clearly defined structured process for our DMP, taking as references the best practices identified from other H2020 and Horizon Europe projects and material provided by the European commission. The following sources were used throughout the AI-EFFECT DMP:
    • H2020 Programme, Guidelines on FAIR Data Management in Horizon 2020 (1) 
    • OpenAIRE H2020 project (2) 
    • Data management, H2020 Online Manual (3) 
    • FAIR Principles (4) 
    • IDS-RAM
This update of the DMP aims to be more explicit about the different data classifications, data governance roles and the different responsibilities within the data management processes.
1.1  Objectives of the work reported in this deliverable
This is the revision of the DMP. The objective of this deliverable is to identify the datasets which are applied in the AI-EFFECT project. It describes how these datasets will be processed and shared to support the Horizon Europe Open Research Data Pilot during the project’s development and after the project’s conclusion. 
1.2  How to read this document
This document can be read independently of other AI-EFFECT deliverables. 


2 Methodology
The Data Management Plan (DMP) is a formal description of the procedures of data handling
during and after a project. A DMP describes the data management life cycle for the data to be
collected, processed, and/or generated. By providing an assessment of data used in a project and
a structured approach for aspects as naming conventions, metadata, and versioning, the DMP
should also support data quality, efficient processing and sharing of data and to ensure it is soundly managed. As part of making research data findable, accessible, interoperable, and re-usable (FAIR), the DMP should include information on:

    • The handling of research data during and after the end of the project;
    • What data will be collected, processed and/or generated;
    • Whether data will be shared/made open access and
    • How data will be curated and preserved (including after the end of the project).

All data will be treated according to EU legislation, and respective national laws.
The objective of this deliverable is to define the project's approach to the management of all the datasets which will be identified and collected in the scope of the AI-EFFECT project. It describes how these datasets will be processed and eventually shared to support the Horizon Europe Open Research Data Pilot during the project’s development and after the project’s conclusion.
In order to do this, this document define a data classification scheme, and then for each classification will describe the actions that will be taken along the FAIR principles.


2.1  FAIR principles
The FAIR data principle is required to be used in EU-Projects by the “Guidelines on FAIR Data Management in Horizon 2020” (EC, 2016). It should support the exchange of scientific data and lead to knowledge discovery and innovation. The FAIR data acronym summarizes the following principles:
    • Findable data: Clear naming and versioning of (meta-) data, easy to find by both humans and computers
    • Accessible data: It is clearly specified how the data is made available, including needed tools, protocols, authentication, and authorization
    • Interoperable data: The published data uses standards and vocabularies that allow interoperability with applications and workflows for analysis, storage, and processing
    • Re-usable data: The goal of the FAIR is reusability; therefore, it is clearly defined when and for which duration data is made available and under which licensing the data was published
The AI-EFFECT consortium will publish data under the FAIR principle whenever possible. The FAIR data management approach enables the exchange of scientific data which fosters knowledge discovery and innovation. 
2.2  Data classification scheme
In order to manage and govern data effectively, it helps to have a data classification scheme. This provides a starting point for defining the data management processes that need to be associated with each of these classifications. In this project we define the following classifications.
It should be noted that within this project, all data is treated as public data unless otherwise specified by the creator (see Section 2.3 for the definition).

2.2.1 Open Information
Description: Data classified as “Open Information” is intended to be freely available and accessible to anyone without restrictions. This type of data generally does not contain sensitive information and can be shared both within and outside the organization. Examples include project deliverables, press releases, and general website content.
2.2.2 Internal Information
Description: Data classified as “Internal Information” is intended for use only within the project. While this data may not be considered highly sensitive, it is still restricted to employees or authorized personnel. This classification allows the project to have some control over what it communicates with the outside. Examples include internal policies, project documents and drafts. 
2.2.3 Restricted Information
Description: Data classified as “Restricted Information” contains information that requires a higher level of protection due to its sensitivity. Access to this data is limited to specific individuals or groups based on their role within the project. Examples include proprietary data, confidential reports and trade secrets.
2.2.4 Personal Information
Description: Data classified as “Personal Information” (sometimes referred to as Personally Identifiable Information, PII) falls under the GDPR. This classification includes any data that can be used on its own or with other information to identify, contact, or locate a single person, or to identify an individual in context. Examples include names, (e-) mail addresses, employment details. 
Access to this data needs to be granted in compliance with the GDPR and limited to those consumers/users (see roles in section 2.3) that fall under the conditions laid out in https://gdpr-info.eu/art-6-gdpr/ 
2.2.5 AI Generated Information
Description: Information classified as “AI Generated Information” falls under the EU AI Act. This classification includes any data or object that was created (in part or entirely) by an AI system (see definition). This classification can be applied in addition to any of the other classifications. 
2.2.6 Conclusion
These classifications help organizations manage and protect their data effectively by ensuring that the appropriate level of security and access control measures are in place. Data Governance Roles
Within the data management processes, several roles need to be identified to determine who is responsible for (or who does) what where and when.
These roles are not fixed for all data in the project. Different people and organizations may have different roles in different data activities.
For the data governance roles, the project adapts the roles proposed by the IDS-RAM:
    • Create: create an object, e.g. software by programming or data from reading a sensor
    • Own: own an object or hold the corresponding license or right according to local rules and regulations
    • Certify/verify: e.g. certify software according to the IDS certification scheme or verify authenticity of data
    • Publish: share meta data on objects such as data, apps, services, etc.
    • Provide: technically provide the object
    • Consume: technically receive the object
    • Use: make use of an object in a business model that does not consist of an intermediary function (see below)
    • Delete: Delete, eliminate or turn object off
The AI-EFFECT Project’s DMP focusses on the following roles:
    • Create (creator)
    • Own (owner)
    • Publish (publisher)
    • Provide (provider), in our role model, the provider is also responsible for deleting any information when appropriate (in agreement with the creator/owner)
    • Consume (consumer)
We add one additional role for Personal Information: - Subject (of the information): when information is Personal Information (see below), the Subject is the individual that the data describes.
3 Data Management Plan
This section will describe per classification how the different FAIR principles are realized.
For the purpose of this section, when the term ‘information’ is used, it may refer to documents, structured data, visualizations, audio recordings or any other representation of information. 
3.1  Open Information
In the case of Open Information, the creator, owner, publisher and provider roles are held by members of the project. Consumers may be other members of the project, or they may be anyone from the general public.
Since this concerns the main publications of the project the ambitions to comply with the FAIR requirements are high.
3.1.1 Findable
    • The creator or owner registers the information in an indexed resource, referred to as a catalog from now on. 
    • Consumers may find the data in this catalog and retrieve it from the provider.
3.1.2 Accessible
    • Providers will make the information available through an appropriate protocol.
    • Users will be able to access this data without restriction.
    • Open data are typically not deleted by the provider unless they were found to contain errors and replaced by an updated publication.
3.1.3 Interoperable
    • Creators will design the information to comply with relevant standards 
    • Project document templates for reports
    • Standardized data models for structured (meta) data (see Appendix A for an overview of potential standards)
        ◦ If no standards are available, the data model is documented and published alongside the information
3.1.4 Reusable
Upon publication, the owner or creator will provide the publisher with the following information:
    • A license (typically an open source or creative commons license) describing the conditions under which a consumer may use the information.
    • Owners are encouraged to select an appropriate license from:
            ▪ https://chooser-beta.creativecommons.org/ for documents, data sets or other information representations
            ▪ https://opensource.org/licenses for software
    • A rights statement that describes any IP or copy rights that the owner and/or anyone else holds over the information.
        ◦ Owners are encouraged to select an appropriate rights statement from https://rightsstatements.org/page/1.0/?language=en 
The publisher will provide this information in the catalog
3.2  Internal Information
In the case of Internal Information, the creator, owner, publisher and provider roles are held by members of the project. Consumers are other members of the project. In rare cases, this information may be shared with consumers  zfrom outside the project.
Since this classification concerns almost any (draft, sketch, etc) information that is created in the project, the ambition here is not as high.
3.2.1 Findable
    • Creators will save their information in the appropriate folders in the file sharing infrastructure that is available to the project.
    • Consumers internal to the project will rely on agreements made in the project to find the information they need.
    • Consumers outside of the project will in principle not have access to this information, unless agreed upon by the owner.
3.2.2 Accessible
    • The provider will maintain the file sharing infrastructure and grant access to the appropriate parties.The provider will also provide any licenses to make use of the infrastructure in case a proprietary platform is being used.
    • If the owner decides to share the information with non-project members, they will make appropriate arrangements with the provider to make that information available to third parties.
3.2.3 Interoperable
    • There are very few requirements on interoperability, but creators should keep in mind that if the information will eventually be published as Open Information, they will at that point need to comply with information standards (see Appendix A).
3.2.4 Reusable
    • Internal Information is not meant to be shared, to this end, any information falls under the project agreement and no additional license or rights statements need to be supplied.
    • If the owner of the information decides it is prudent to share the information with specific individuals or organizations (if they decide it can be shared with anyone it should be treated as open information) outside the project, a data sharing agreement will have to be created describing how the consumer is allowed to use the data.
3.3  Restricted information
Restricted information can be data that underlies a publication or internal data that is considered extra sensitive to the point that only those with explicit permission may have access to it. Unlike ‘internal information’, restricted information is still meant for sharing, just with only those that have received explicit permission from the publisher or owner. For this purpose, most of the requirements for ‘Open Information’ also apply to ‘Restricted Information’.
3.3.1 Findable
    • If the information was used as input for a publication: the same requirements as for ‘open information’ apply.
    • if the information is meant for internal use only, the same requirements as for ‘internal information’ apply.
3.3.2 Accessible
    • The provider provides an access-controlled environment in which only  consumers with whom the owner of the information has a data sharing agreement (see below) have access.
    • upon request of the owner, additional security measures may be adopted (like encryption).
3.3.3 Interoperable
    • If the information was used as input for a publication: the same requirements as for ‘open information’ apply.
    • If the information is meant for internal use only, the same requirements as for ‘internal information’ apply.
3.3.4 Reusable
    • The owner of the information will provide a data sharing agreement stating addressing rights, licensing, and use limitations.
    • Any consumer who wishes access will need to agree on a data sharing agreement with the owner.
It is the sole prerogative of the owner to grant or deny access to the information. Personal Information
Personal information falls under the GDPR. This means it is treated as restricted with the modification that it is not the prerogative of the owner to share the data: the owner and the provider also have the responsibility to comply with the GDPR.
Since the data management requirements are high and difficult to meet, especially after termination of the project, collection of personal data will be minimized, and all personal data will be deleted before the termination of the project.
3.4.1 Findable
Same provisions apply as for Restricted Information.
3.4.2 Accessible
Same provisions apply as for Restricted Information, with the following additions.
    • The information will be deleted by the provider at the termination of the project.
    • If the information is collected for the purpose of research and needs to be retained after the completion of the project, it is the responsibility of the owner to find an (alternative) provider willing and able to provide the information, compliant to the GDPR regulations, after the project is terminated.
    • The provider needs to allow subject of Personal Information to claim the rights that are granted to them by the GDPR, most notably:
        ◦ Request an overview of the information that the project has stored about them (Right of access)
        ◦ Request that information is corrected in case it is erroneous (Right to rectification)
        ◦ Request that data be deleted (Right to erasure/ Right be forgotten)
3.4.3 Interoperable
    • The GDPR grants the subject of the information the right to data portability, meaning:
        ◦ in a structured, commonly used and machine-readable format and have the right to transmit those data to another controller without hindrance from the controller to which the personal data have been provided.
3.4.4 Reusable
    • Same provisions as for Restricted Information, with the following additions.
    • The owner and creator of the information shall clearly state the purpose limitation with which the information was collected
    • Personal Information may only be shared if the subject (the person who the information is about) has given permission to do so.
    • Any data sharing agreement must contain the purpose limitations of both the creator/owner as well as the consumer.
3.5  AI Generated Information
This classification is in addition to any of the other (open information, internal information restricted information or personal information). This means that in addition to the requirements laid out here, the data management plan for the other classification should also be followed. In case of conflicts, the most stringent plan applies.
For the purpose of this Data Management plan, we distinguish between a couple of scenarios involving AI:
    1. AI for reporting: Text, images, video or other media generated for the purpose of reporting or dissemination activities. Here, AI is not used for the primary research activities, just for reporting on them.
    2. Using AI: Research data or other artifacts generated with AI. In this case, AI has been used during the research itself.
    3. Creating AI: In this case, the research focusses on creating an AI system as defined by the AI Act.
The additional requirements for ‘AI Generated Information’ come under the Reusable (FAIR) principle. Under reusable, the FAIR suggest that data is associated with detailed provenance. This is particularly relevant as the AI Act demands (in the case of ‘high risk’ applications) certain meta data to be stored. However, depending on the 3 subclassifications above, different (meta)data needs to be provided.
3.5.1 AI for Reporting
When using AI for reporting, We recognize two scenario’s. In the first scenario an artifact (a diagram, a piece of text etc) was in its entirety created using AI, in this scenario the material that was generated should have an attribution that states:
This [material/visual/text/...] was (in part) generated using AI. It was generated using [model name]+[model version] at [date]
In the second scenario, the material was primarily created by the author, but the author was aided by AI (think about tools that improve  grammar or AI assisted drawing tools). In this case additional attribution is not necessary.
3.5.2 Using AI
When using AI for the purpose of creating research artifacts, like generating data, the attribution needs to be more formal and more exact. Withing the scope of this data management plan the following information needs to be supplied (conforming to the prov-o standard)
    • The Activity (the run of the AI system) that produced the dataset, including when the Activity took place
    • The AI system, including its version
    • The input data(sets), including any prompts or configurations like ‘temperature’, that the AI system used to produce the result.
3.5.3 Creating AI
When the purpose of the research is to create an AI system, the trained AI model needs to be published either as Open Information, Restricted Information or as Personal Information, depending on the classification, with the corresponding metadata. Since these models are designed in the context of the energy system, it is presumed they will fall under the high risk classification of the EU AI Act. As such the following datasets need to be published as well:
    • The training dataset
    • The validation dataset (testing the validity of the model)
    • Prompt-response logs that register the models inputs and outputs
    • Architectural documentation that addresses the following requirements of , including-but not limited to:
        ◦ a written strategy for regulatory compliance and conformity assessment.
        ◦ procedures used in the development of the AI system and procedures for quality control and quality assurance
        ◦ examination, test and validation procedures to be carried out before, during and after the deployment of the system.
        ◦ documentation of the systems and procedures used for data collection, data analysis and labelling of training data
        ◦ a risk management system that addresses foreseeable risks, including
            ▪ health risks (usually not relevant in this domain)
            ▪ safety risks
            ▪ fundamental rights risks (think about access to energy, rights to participate in a market etcetera)
4 Data summary
The AI-EFFECT project strives for a consistent and transparent data management. This will support the project management as well as assist the cooperation between the project partners. With a forward-looking data management, the exploitation of the project is facilitated for the project partners as well as of all potential external beneficiaries like research institutes, universities, or R&D departments of companies.
All partners of the project consortium support the policy of open-source approaches. If possible, work and results will be published in an open-source manner. Publishable datasets will be considered to be published on open data platforms in addition to the AI-EFFECT deliverables. Document collections such as OpenAIRE and Zenodo will be considered for the publication and collection of AI-EFFECT reports, results, research papers, etc.
In this initial version of the AI-EFFECT project Data Management Plan, a provisional list of datasets related to the project’s demo nodes is included below. For each of the use cases, however, an in-depth analysis of the required datasets will be performed through the whole duration of the project and the list of datasets, as well as their description will be updated during the whole life of the project.
4.1  UC1: Multi Energy and Sector Coupling
This series contains all the datasets related to the creation of AI systems for the multi-energy and sector coupling usecase of the AI-EFFECT project. 
4.2  Regulatory Compliance Strategy for UC1

Regulatory Compliance 
publisher	DTU
license	TBD
policy	Open Information
status	Planned

4.2.1 AI System for UC1
AI System for UC1 
publisher	DTU
license	TBD
policy	Open Information, Creating AI
status	Planned

4.2.2 Training Data Collection and Processing Procedures for UC1
Training Data Collection and Processing Procedures

publisher	DTU
license	TBD
policy	Open Information
status	Planned

4.2.3 Test and Validation Procedures for UC1
Test and Validation 
publisher	DTU
license	TBD
policy	Open Information
status	Planned

4.2.4 Prompt Response Log for UC1
Prompt Response Log 
publisher	DTU
license	TBD
policy	Open Information, Using AI
status	Planned

4.2.5 Training data set for UC1
Training data set 
publisher	DTU
license	TBD
policy	Open Information
status	Planned

4.2.6 Validation data set
Validation data set 
publisher	DTU
license	TBD
policy	Open Information, Using AI
status	Planned

4.3  UC2: Transmission Congestion Management
This series contains all the datasets related to the creation of AI systems for the transmission congestion management usecase of the AI-EFFECT project. 
4.3.1 Regulatory Compliance Strategy for UC2
Regulatory Compliance Strategy 

publisher	TU Delft
license	TBD
policy	Open Information
status	Planned

4.3.2 Validation data set for UC2
Validation data set 
publisher	TU Delft
license	TBD
policy	Open Information, Using AI
status	Planned

4.3.3 Training Data Collection and Processing Procedures for UC2
Training Data Collection and Processing 
publisher	TU Delft
license	TBD
policy	Open Information
status	Planned

4.3.4 Prompt Response Log for UC2
Prompt Response Log 
publisher	TU Delft
license	TBD
policy	Open Information, Using AI
status	Planned

4.3.5 Test and Validation Procedures for UC2
Test and Validation Procedures 
publisher	TU Delft
license	TBD
policy	Open Information
status	Planned

4.3.6 AI System for UC2
AI System for UC2 
publisher	TU Delft
license	TBD
policy	Open Information, Creating AI
status	Planned

4.3.7 Training data set for UC2
Training data set 
publisher	TU Delft
license	TBD
policy	Open Information
status	Planned

4.4  Energy efficiency, management and sharing for local energy communities
This series contains all the datasets related to the creation of AI systems for the Energy efficiency, management and sharing for local energy communities usecase of the AI-EFFECT project. 
4.4.1 Test and Validation Procedures for UC4
Test and Validation Procedures 
publisher	INESC-TEC
license	TBD
policy	Open Information
status	Planned

4.4.2 Training data set for UC4
Training data set 
publisher	INESC-TEC
license	TBD
policy	Open Information
status	Planned

4.4.3 Regulatory Compliance Strategy for UC4
Regulatory Compliance Strategy 
publisher	INESC-TEC
license	TBD
policy	Open Information
status	Planned

4.4.4 Prompt Response Log
Prompt Response Log 
publisher	INESC-TEC
license	TBD
policy	Open Information, Using AI
status	Planned
|
4.4.5 Training Data Collection and Processing Procedures for UC4
Training Data Collection and Processing Procedures 
publisher	INESC-TEC
license	TBD
policy	Open Information
status	Planned

4.4.6 Validation data set for UC4
Validation data set 
publisher	INESC-TEC
license	TBD
policy	Open Information, Using AI
status	Planned

4.4.7 AI System for UC4
AI System for UC4 
publisher	INESC-TEC
license	TBD
policy	Open Information, Creating AI
status	Planned

4.5  DER integration into Distribution Systems
This series contains all the datasets related to the creation of AI systems for the DER integration into Distribution Systems usecase of the AI-EFFECT project. 
4.5.1 Regulatory Compliance Strategy for UC3
Regulatory Compliance Strategy 
publisher	Fraunhofer
license	TBD
policy	Open Information
status	Planned

4.5.2 Training data set for UC3
Training data set 
publisher	Fraunhofer
license	TBD
policy	Open Information
status	Planned

4.5.3 Validation data set for UC3
Validation data set 
publisher	Fraunhofer
license	TBD
policy	Open Information, Using AI
status	Planned

4.5.4 Prompt Response Log for UC3
Prompt Response Log 
publisher	Fraunhofer
license	TBD
policy	Open Information, Using AI
status	Planned

4.5.5 AI System for UC3
AI System for UC3 
publisher	Fraunhofer
license	TBD
policy	Open Information, Creating AI
status	Planned

4.5.6 Training Data Collection and Processing Procedures for UC3
Training Data Collection and Processing Procedures 
publisher	Fraunhofer
license	TBD
policy	Open Information
status	Planned

4.5.7 Test and Validation Procedures for UC3
Test and Validation Procedures 
publisher	Fraunhofer
license	TBD
policy	Open Information
status	Planned

5 Appendix A: table of relevant information standards
This appendix contains an overview of (potebntially) relevant information standards 
Standard	Publication	Description of domain
DCAT	https://www.w3.org/TR/vocab-dcat-3/	Data model for data catalogs, data sets, distrubutions and associated metadata
PROV	https://www.w3.org/TR/prov-o/	Data model to describe data lineage/provenance
DQV	https://www.w3.org/TR/vocab-dqv/	Data model for data quality metadata
odrl	https://www.w3.org/TR/odrl-model/	Data model to describe data policy and compliance requirements
IEC-CIM	https://cimug.ucaiug.org/CIM%20Model%20Releases/Forms/AllItems.aspx	Series of standards to describe the electrical grid (iec-61970), electricity markets (iec-62325) and power grid asset management (iec-61968)
IEC-61850	https://iec61850.dvl.iec.ch/	IEC standard for substation automation
sosa/ssn	https://www.w3.org/TR/vocab-ssn/	A standard to describe sensors, observations and measurements
qudt	https://www.qudt.org/	A standard that defines units, quantities and datatypes. 
Open energy ontology	https://openenergyplatform.org/ontology/	Ontology that describes energy systems, under development, promising, but not very mature yet
saref	https://saref.etsi.org/	The Smart Applications REFerence (SAREF) suite of ontologies forms a shared model of consensus intended to enable semantic interoperability between solutions from different providers and among various activity sectors in the Internet of Things (IoT), thus contributing to the development of data spaces.
		

