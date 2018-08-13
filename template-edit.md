# Oregon-State-Data-Management-Plan Template
Table of Contents  
[Data Management Implementation Plan](#data-management-implementation-plan)  
[Data Management Units](#data-management-units)  
[Data Collection](#data-collection)  
[Data Documentation](#data-documentation)  
[Quality Control](#quality-control)  
[File Organization](#file-organization)  
[Formats](#formats)  
[Storage](#storage)  
[Backup](#backup)  
[Workflow Internal Data Sharing](#workflow-internal-data-sharing)  
[Data Use](#data-use)  
[Protection for Sensitive and Confidential Data](#protection-for-sensitive-and-confidential-data)  
[Management of Physical Samples](#management-of-physical-samples)  
[Data Publication](#data-publication)  
[Data Archival](#data-archival)  
[Roles and Responsibilities](#roles-and-responsibilities)  

*[Instructions in this document will appear in this format. The expectation is that all instructions will be deleted from this document after it is completed. All other sections and text are provided as suggestions to help you implement your data management plan. Delete and modify them as you see fit so that this document ends up being useful to you. Extra guidance, suggestions and examples can be found [here](https://here) If you have feedback about this template, please contact ResearchDataServices@oregonstate.edu  ]*

### Project information

**Instructions**  
*[Include basic information about the project.]*

**Text**

Project: *[Project Name]*  
Website: *[Website of the project]*  
PI: *[Principal investigator of the project]*


## Data Management Plan and other Documentation
Instructions  
*[Include a reference to all the documents that may affect decision making about datasets in this project.]*  
Text  
- 	The data management plan that was submitted with the grant proposal for this project can be found in *[blank]*  
- 	Data Sharing Agreement between *[blank]* and *[blank]* can be found in *[blank]*
- 	Contracts between *[blank]* and *[blank]* that involve data management can be found in *[blank]*  
- 	Department and college policies with data management consequences *[blank]*  
- 	Oregon State University Open Access policy can be found [here]( https://cdss.library.oregonstate.edu/sites/default/files/osu_openacesspolicy_final_single_page.pdf). The policy directs faculty to submit an electronic copy of the author's accepted (post-peer review, pre-typeset) manuscript of their articles to OSU Libraries for dissemination via the ScholarsArchive@OSU institutional repository.   
- 	Oregon State University’s University Data Managmeent, Classification, and Incident Response policy can be found [here]( https://is.oregonstate.edu/ois/data-management-and-classification-overview). It classifies data into Unrestricted, Sensitive and Confidential and defines standards of care for each kind to protect confidentiality, integrity, and availability of data.    


## Data Management Units

Instructions  
*[Define datasets that will be created during this project, and group them according to different management needs. Describe relevant general information about the data groups: are they observational, experimental, simulation, model output or assimilation datasets; How will they be collected? How much data is expected?]*  
Text

*[blank]* groups of datasets will be generated during the course of this project.

1 – Dataset Group 1 *[change name to more informative name]*  
	Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
	Collection strategy: *[blank]*  
	Amount of data expected: *[blank]*  

2 – Dataset Group 2 *[change name to more informative name]*  
	Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
	Collection strategy: *[blank]*  
	Amount of data expected: *[blank]*  


## Data Collection
Instructions  
*[Information relevant to how data will be collected, captured or created]*

Sampling sites: *[Include information with description of sampling sites including important data about them such as location, official names to be referred to, instrumentation in each sampling site, etc. ]*  

Existing protocols: *[Include the location of protocols relevant to the research that already exist, like lab safety protocols, sampling protocols, instrument installation protocols, etc. Include here all the contextual information relevant for the use of the protocol that is not explained in the protocol itself ]*  

Name: *[name of protocol]*  
Location: *[where to find the protocol]*  
Expected use: *[who should use the protocol, when]*  
Training: *[who will train new researchers. Who to ask when there are questions about the protocol.]*  

New protocols: *[For projects that involve the creation of routinely creating new protocols, describe the process of creating new protocols.]*  

Process *[Defines the process to create the protocol]*  
Approval *[Process to approve the protocol, and who should approve it]*  
Tools *[If special tools will be used to create the protocol, specify]*  
Storage *[Where it should be saved, with which file naming strategy]*  
Update *[How to update the protocol]*  
Expected use *[Who should use the protocol, and for which circumstances]*  

Instrumentation: *[Include relevant information about the instruments that will be used to collect data, like where to find instructions, maintenance to ensure that the sensors will work correctly, etc.]*  

Software: *[Include relevant information about the software that will be used to generate data. Where to access the documentation. Intellectual property information about the software to be aware of. ]*  


## Data Documentation

##### Rationale and resources
Data documentation is also referred to as metadata. Ideally, all research data generated through the development of a research project should be documented from the beginning of the project. The earlier the documentation process begins, the less likely that details about methodology will be forgotten. Planning about data documentation in the early stages of a project also ensures that data documentation will be thorough.

When designing the documentation strategy think that a person not familiar with the project should be able to understand the important aspects of the project, and all the experiments, without having to talk to any person.

Using strategies to document datasets is the best way of ensuring that it will happen. The preferred strategy would be using a **data standard and/or metadata standard**. These ensure that the data and metadata will be recorded a certain way, and therefore will be thoroughly documented, the relevant information will be easily findable, and the data can be shared easily with others. Find existing data standards and metadata standards in http://rd-alliance.github.io/metadata-directory/

In spite of the wide variety of data and metadata standards available, it is possible that you won’t find the perfect data standard for your research. Sometimes it is because your research is too specific, and there is nothing that will quite work. Some other times it is because the learning curve to establish a new standard in the lab is too steep to take on. Other tools, often easier  to implement, are lab specific templates and readme files.

**Lab specific templates** require some prep work, but they are a very flexible tool. They add structure to research notes, with helps researchers record thorough documentation. The structure also makes it easier to search and find information in the notes. Templates can be adapted easily to very discipline specific formats, and they can be designed using the tools that the research group is used to working, which makes its implementation easier.  For more about templates as a documentation tool, see [Kristin Briney’s blog post on Templates]( http://dataabinitio.com/?p=531).

**Readme files** are a flexible way of adding documentation to data files. Readme files are plain text files, that can be edited with any text editor, and can be placed in any directory where they are needed. Readme files work very well, for example, to document the folder structure for a particular project. They can be used to record any relevant information about a dataset, though. For more information see [Kristin Briney’s blog post on README.txt]( http://dataabinitio.com/?p=378).

Here are some ideas of the kind of information that should be recorded for each dataset:
*	General:
    * Authors, collaborators, contacts, and people responsible for the dataset
    * Context of the dataset: research project, abstract, hypotheses…
    * Dates of creation, collection, dates when the dataset was updated…
    * Software and other tools needed to access the data
    * Methods used for the collection of the data, and quality control.
    * Level of quality control that each data point has gone through.
    * Standards that are being used
    * File names of all the files in the dataset, and description of what they contain. File naming conventions used in the dataset.
    * Acronyms and abbreviations used in the dataset.
    * References useful to understand or interpret the dataset.
*	For tabular data:
    * Units
    * Description of all column headers
    * Value used for null value.
*	For images:
    * Consider editing the image metadata with a program like [Exiftool by Phil Harvey]( https://www.sno.phy.queensu.ca/~phil/exiftool/).
    * Keep information about image provenance: for images that have been modified in some way, keep information about where is the original image, which changes have been performed, and why.   
*	For sensitive and/or confidential data:
    * IRB documentation
    * How will the data be protected?
*	For code:
    * Consider the good practices in [Wilson et al. (2014) Best practices for scientific computing](https://doi.org/10.1371/journal.pbio.1001745), which includes the following.
    * Embed the documentation for a piece of software in that software.
    * Document interfaces and reasons, design and purpose, not implementations or mechanics.


## Quality Control
##### Rationale and resources
It may be useful to design different levels of quality control. For example:

**Level zero (L0):** Data as it is downloaded directly from an instrument or model. This data is often in binary format, impossible to understand or look at by a human unless it is processed by a program. These programs tend to be proprietary and they may or may not perform operations on the data. This data level may not exist. For example: binary files coming from a temperature sensor permanently installed in a stream.  
**Level one (L1):** Raw data in a format that is understandable by a human. There have been no corrections on these data. For example, a csv file obtained after running the programs supplied by the company that manufactured the instrument.  
**Level two (L2):** Verified data that have undergone quality control, including but not limited to:
*	Detecting sensor malfunctioning
*	Assessment of outliers
*	Calibration
*	Corrections for sensor drift or offset, data artifacts, etc.

Level two data are the best data that a researcher could use. Level two data should not include data that have undergone quality control procedures that are subjective to the researcher. When quality control is not necessary, L1 and L2 data may be the same.  
**Level three (L3):** L2 data that have been analyzed to answer specific research questions. Typically, this is the data that will be used to create figures in a publication. For example, if a principal component analysis was used to analyze three years of temperature data and published in a figure as part of a peer-reviewed article.  




## File Organization

Lab material must be connectable to their context in the real world (lab notebook, instrument settings, etc.). Proper lab data management will ensure this is possible.

- The directory containing experimental output should have the following format:
YYYY-MM-DD_notebook-page_descriptive-name
- The raw experimental data should be exported into an appropriate non-proprietary, long-term file format.
- Each directory should have a clearly labeled summary file (image, text file/document, or graph). The summary file should be printed out and placed in the lab notebook.



## Formats
##### Rationale and resources

Formats that will be better at long term preservation are formats that are platform independent (can be accessed from Linux, Mac and Windows), in an open format (no proprietary formats), and character based (not in binary format). There can be exceptions to all of these for the right reasons. For example, some data standards that are widely used in some disciplines, like netCDFs, save data in binary format.  
See [eCommons: Cornell's Digital Repository. Recommended file formats](http://guides.library.cornell.edu/ecommons/formats) for a table with existing formats for different types of content, and their probability for full term preservation.



## Storage  



## Backup



## Workflow Internal Data Sharing
Rationale: setting expectations about how and when datasets will be shared internally will minimize conflict during the project.



- Datasets will be shared internally             **_[specify when researchers are expected to share their datasets. Some examples: as soon as possible after the data is collected/at the end of the sampling season/6 months after it is collected/on January of each year/when a researcher of the Project requests it ]_**.

- Datasets will be shared internally with         **_[who? Some examples: all the members of the team/members of the team approved by the IRB/the data manager of the project/the researcher who requested the dataset]_**.

- Datasets will be shared internally in                   format **_[is there an expected format? For example excel, or csv, or spss, or…]_**.

- Datasets will be shared internally                 **_[at which quality level? For example: after a quality control level has been assigned to each point following the schema in X / after following the protocol X for quality control/at any quality control level, as long as the documentation clarifies the quality control procedures that have been followed /only if all the data points have been subject to the whole quality control process outlined in X]_**.

- Datasets will be shared internally accompanied of                **_[which documentation? For example: a readme file outlining at least the methods followed for data collection, the quality control procedures that have been followed, and a data dictionary/documentation using the template X/documentation using the metadata template X]_**.

- Datasets will be shared internally by                   **_[how are the datasets going to be delivered? For example: by e-mail/by depositing them in Box/Google drive/external hard drive/shared drive/website]_**.

- When a member of the Project uses a dataset shared by another member of the team        **_[how will the use be notified? For example: a courtesy e-mail will be sent to the contact person/no notification will be needed at this stage/the member of the Project using the shared data will write his/her name in a log]_**.

- When a new version of a dataset is generated, it will be notified to the other members of the Project that may want to use the dataset by             **_[example: sending a general e-mail to the whole group/documenting in the documentation file the new version and sending individual e-mails to the members of the team that are known to be using the dataset]_**.

**_[Include other workflow details that will be useful if necessary. For example, there may be details in the data management plan that can be outlined or detailed here. For example, when will the datasets be made publicly available? Who will decide when to make the dataset available if there are several researchers working with them?]_**



## Data Use



## Protection for Sensitive and Confidential Data



## Management of Physical Samples



## Data Publication

##### Acknowledgment of Data Use


Rationale: Most of the data management responsibilities outlined in the final section require a lot of time and effort. Often, datasets are shared within members of the same project and the use of these datasets improves or makes possible scholarly outcomes  such as publications of articles, book chapters, presentations in conferences, proceedings, etc. It is necessary to have a common understanding on how to acknowledge the role of data managers, data creators, data analysts in the research process. These roles may not be appropriate as manuscript authors, but there are many other options. Acknowledging these roles is not a legal matter (no law requires it), but it is an ethical one. Responsible conduct of research involves acknowledging other people’s roles in managing data. Acknowledging the roles may also have an impact of the careers of researchers involved.    


**_[Decide what are the procedures that you will follow to acknowledge data management roles, and if there are any preferred methods. This template lists the options in order: options that follow best practices are noted at the beginning, while practices that we discourage are noted at the end. We use here “data management” as a general term, but consider changing it for more specific roles. For example, you may want to consider offering co-authorship to the researchers involved in data collection and data quality control as authors in data publications, and adding the researchers involved in instrumentation maintenance in the acknowledgements]_**


All members of the Project involved in roles related to data management will be acknowledged in some way. Specifically:



- Members of the Project that were involved in data management **_[change to a more specific role]_** will be offered co-authorship to papers that make use of their data. Co-authorship will require participation in the interpretation of the data, writing, or critical review of the manuscript, approval of the final manuscript. **_[if the group defines authorship using a specific set of criteria, include a link to these criteria here. A few examples of current definitions of authorship can be found in https://publicationethics.org/resources/discussion-documents/what-constitutes-authorship-june-2014]_**. The offer for co-authorship may be accepted or declined.


- Datasets will be published separately from the research in a repository or as an article in a data journal **_[change if there are more discipline specific options]_**. Members of the Project with a significant data management contribution will be listed as co-authors in the data publication. Every member of the Project that makes use of the published datasets will cite the dataset and list it in the reference list in their publications.  



- When possible, publications will be made in journals that use the CRediT authorship taxonomy (http://docs.casrai.org/CRediT) or similar. The roles of each of the members of the Project involved in data management will be documented using the appropriate roles.

## Data Archival



## Roles and Responsibilities
Rationale: Data management takes time and effort. In order to not oversee any important data management action, it should be clear to all the members of the team who is responsible for each of them.


##### Role definitions: **_[adapt the definition of each of the roles for the Project. These roles are defined so that this document will not need to be adapted every time that there are changes within the Project team. These definitions should reflect as accurately as possible the roles in the project. For example, if the project will have Postdocs but not technicians, rename the Researcher role to Postdoc. For example, if there are going to be two kinds of students (field students and lab students) that will have different data management roles, these should be outlined here. For example, if the project is going to have a data manager, outline the role here.]_**


**Principal Investigator (PI):** leads the Project. It is usually designated by the funder. If there is no funder or the funder does not designate the principal investigator, it will be person providing leadership to the Project.

**Faculty Investigator:** they actively perform research on all or a part of the research Project. They may provide active mentorship to students.

**Team member:** they contribute to the scientific development or execution of a study in a substantive, measurable way (research/postdoctoral fellows, technicians, associates and consultants).

**Student:** member of the Project pursuing a degree. Undergraduate, master, PhD or others

##### Responsibilities **_[adapt the definition of each of these responsibilities to the Project. Add more, or remove if necessary. Decide who (which role) is going to be responsible for each of these]_**




**DMP Implementation:** responsible for ensuring Data Management Plan and the Internal Data Sharing Plan move from planning into implementation; ensure that any practices, responsibilities, policies outlined in the plan are followed; ensure that new members of the Project will receive data management training; responsible for maintaining the Data Management Plan and the Internal Data Sharing Plan up to date, and making sure that all members of the Project understand and are prepared to apply the changes.


 Responsibility of: **_[complete with one of the roles defined above]_**


**Access control:** responsible for regulating access to data based on the roles of the authorized user, whether from the project or not. Access is the ability to perform a specific task, such as view, create, or modify a file. Responsible for granting access to data by members outside of the project when requested during the duration of the project.


Responsibility of: **_[complete with one of the roles defined above]_**

**Protection of sensitive and protected data:** responsible for complying with applicable laws and regulations, institutional policies, and ethical principles governing the conduct of human subjects research, sensitive and protected data.


Responsibility of: **_[complete with one of the roles defined above]_**


**Software creation and maintenance:** responsible for the creation, design, and installation of a software products (e.g. code writing) and maintenance of the system (software update, error correction, enhancement of existing features).


Responsibility of: **_[complete with one of the roles defined above]_**


**Instrumentation maintenance:** responsible for conducting tasks related to instruments such as installation, calibration, testing, and performing maintenance of instrumentation equipment.


Responsibility of: **_[complete with one of the roles defined above]_**


**Data collection/ data generation:** responsible for data collection and creation (research, locate, identify, and measure), data entry, information processing (transcribing and manipulation), data generation (prototyping, models, and database).


Responsibility of: **_[complete with one of the roles defined above]_**


**Data organization:** responsible for maintaining the data in an organized data structure so that it is easy to find (i.e. folder structure, file naming conventions). Responsible for saving the data in the appropriate formats.


Responsibility of: **_[complete with one of the roles defined above]_**


**Metadata generation:** responsible for generating metadata (data description), documentation, using the metadata standards or templates specified in the Data Management Plan.


Responsibility of: **_[complete with one of the roles defined above]_**


**Quality control:** responsible for performing quality assurance  and quality control. It involves testing, reviewing, cleansing of data, calibration, correcting errors, data remediation, and documentation of quality control on the data points.


Responsibility of: **_[complete with one of the roles defined above]_**


**Data analysis:** responsible of various activities related to data analysis such as examining, analyzing, sorting, aggregating, transforming, modeling, visualizing, validating, presenting, to answer research questions.


Responsibility of: **_[complete with one of the roles defined above]_**


**Archiving and preservation:** responsible for assuring archiving and storage, preservation and access to data (and associated metadata) long term (e.g. in a repository, or managed internally).


Responsibility of: **_[complete with one of the roles defined above]_**
