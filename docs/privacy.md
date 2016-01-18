#Protecting Privacy

##Introduction
Open data publishing requires policies and actions to protect individuals and organizations from unintentional breaches of personally identifiable information (PII). The proliferation of digital public records, data contained in social media, inadequate policies for managing and protecting PII, and inconsistent data management practices increase the likelihood that PII can be combined across multiple sources to uniquely identify an individual. This section of the guide is designed to help publishers identify PII, and take steps to minimize the risk and harm of a breach.

##What is Personally Identifiable Information (PII)
Personally identifiable information (PII) is “information about a person that contains some unique identifier, including but not limited to name or Social Security Number, from which the identity of the person can be determined.” [GSA 2014] This description includes both information that directly identifies an individual, such as a name, and information, such as race or gender, that can identify individuals when combined with other information.

The list below describes what might be considered personally identifiable information (PII). It is not meant to be exhaustive but is intended to provide examples and context as to what might be considered PII. 
 
|Personal Identifiers|   
|---------------------|
|Name |
|Social Security number|
|Drivers' licence number|
|Passport number|
|Financial account numbers (bank, credit cards)|
|Taxpayer identification number|

|Contact information|  	
|----------|
|Address|
|Phone number|
|Email Address|

|Other personal data|
|---------------|
|User names|
|Date of birth|
|Place of birth|
|Mother’s maiden name|
|Gender|
|Age|
|Physical descriptors (eye/hair color, height, etc.)|
|Family information (marital status/children/relatives)|
|Sexual orientation|
|Race/ethnicity|
|Religion|
|Education|
|Employment|
|Citizenship|
|Criminal history|

|Medical and biometric data|
|--------------------|
|Signature and handwriting|
|Fingerprints, handprints, and other body scans|
|Photograph|
|Voice recording|
|DNA markers|
|Health, insurance, treatment, or medical information|

|Computing and communications data|
|---------------------|
|User names|
|Passwords|
|Unique device identifier|
|Location/GPS data|
|Camera controls (photo, video, videoconference)|
|Microphone controls|
|Other hardware/software controls|
|Cell tower records|
|Data collected by applications|
|Contact lists and directories|
|Network status|
|Network communications data|
|Device settings or preferences (e.g., security, sharing, status, etc.)|
|Log data (e.g., IP address, time, date, referrer site, browser type)|
|Tracking data (e.g., single- or multi-session cookies, beacons)|
|Forms data|

|Other data|
|-------------|
|Vehicle registration number|
|Vehicle title number|
|Vehicle license plate|
|Other geographic identifiers (coordinates, etc.)|
|Activities|

Privacy law and respective legal standards ultimately determine what constitutes PII.  Therefore, the definition of PII varies by jurisdiction and also on a case-by-case basis. 

##What are Public Agencies Required to Share?
Public records in Pennsylvania are subject to the presumption of openness standard in the Commonwealth’s Right-to-Know Law. This standard dictates that all records are presumed to be open to the public unless:
1. Disclosure is prohibited by law, regulation, or judicial order; 
2. Disclosure is prohibited by privilege, such as attorney-client or doctor-patient privileges; 
3. The requested information meets one of 30 criteria outlined in Section 708 in Pennsylvania’s Right-to-Know Law AND agencies deem the risks of public disclosure outweigh the benefits.

The presumption of openness standard places the burden of proof on agencies to demonstrate any exemption criteria are met. 
Most of the exemption criteria in Section 708 are related to the release of PII, drafts of internal documentation, or records that would pose public risks if released.  It should be emphasized that public agencies can release information that meet the Section 708 exemption criteria if they deem such release in the public’s best interest.  

Additional information about Pennsylvania’s Right-to-Know Law, including a list of Section 708 exemptions, can be found at http://panewsmedia.org/legal/openrecords.

In addition to Right-to-Know laws, individuals may have certain rights to access or be aware of information that pertains to them.  


##Privacy Review Process
Organizations should develop and implement an internal review process to evaluate whether or not to share a particular dataset. Part of this evaluation should include a risk-based approach to assess the probability and severity of a breach. The evaluation can also provide guidance in what data de-identification and anonymization practices would need to be applied prior to release. Additional aspects of the privacy review can include a data quality assessment, and a comparison of how other publishers have handled this dataset.
####Privacy Risk Assessment

This section profiles the development and application of a risk-based approach to appraise the expected consequences of a breach of sensitive information. We first disaggregate the expected consequences of a potential breach into the probability and severity of a breach. We then develop semi-quantitative categories for the probability and severity of breach and apply them using a risk matrix. 

The probability of a breach is influenced by 
- the quantity, location, and format of PII;
- respective modes of access; and
- the degree to which individuals can be uniquely identified.

For example, client names and addresses stored in only one location with clearly-defined access policies and consistent formatting are less likely to be breached than names and addresses of clients stored in multiple locations with inconsistent access restrictions and inconsistent data formats.  

Probability of a breach can be mitigated by effective data management and evaluation practices.

The severity of a breach includes potential liability to both individuals and organizations.  The severity are a breach of PII are influenced by

- the sensitivity of the information to potential misuse;
- the context in which the information is used by the publisher; and 
- obligations governments may have to protect the information

For example, an employee directory and contact information are less sensitive to misuse than a contact listing of undercover police detectives. Similarly, the consequences of breaching a list of student names are different than breaching a list of students by names that are seeking treatment for substance abuse. Both contain the same PII, but the context of uses poses different potential consequences in the event of a breach.  

In some cases, PII protections are defined by law or regulation. Names of political campaign donors often must be publicly released, whereas regulations like HIPAA and FERPA restrict the release of PII by law.

The expected consequences of a breach are informed by both its probability of breach and severity of consequences. Ideally, both the probability and the severity of an inadvertent PII breach would be known quantities, and the consequences would simply be the product of the two, or consequence = probability × severity. However, it is difficult to accurately forecast the probability or severity of an unintended breach.  

Thus, governments often employ semi-quantitative techniques to assess expected consequences. Staff first define categories for both the the probability and severity of a breach.  The probability and severity categories are then assembled into the rows and columns, respectively, to define a risk matrix. The following table shows an example risk matrix that includes four probability categories (near certain, likely, possible, and improbable) and four severity categories (insignificant, moderate, major, and critical). However, staff can use choose any number of categories and respective definitions. 

Risk matrices have been applied to a wide variety of public sector decision making, including assessing health and safety for disaster response crews [OSHA 2015], prioritizing river restoration projects [Thorne et al. 2014], and estimating the local risks of climate change [World Bank 2015].

Since the selection and definition of severity categories are subjective, staff might openly discuss examples of consequences that meet the various severity criteria. Participation by multiple staff can also help balance the subjectively inherent in completing a risk matrix. Similarly, since the assignment of breach probability is subjective, local governments and other data owners may find it helpful to develop a common definition of probability categories. For example, Table 4 couples the probability categories with a ranges in expected probabilities (“near certain” implies 90%-100% probability; “likely” implies 50%-90% probability; “possible” implies 10%-50%; and “improbable” implies 0%-10%). 
Once the characteristics of the risk matrix have been defined, staff then attribute a unique probability and severity category to each PII field, which then places each PII in a unique cell in the risk matrix. Table 1 shows the attribution of probability and severity categories to three hypothetical data sets:
A list of a five employee names, emails, and professional certifications that constitute a small municipal department that is otherwise available through the agency’s website;
A list of around 3,000 school district students and their home address stored on district servers with outdated firewalls to which many individuals have remote access;
A database of 311 non-emergency complaints (approximately 50,000 per year), including the location of the requested service, the address of the complainant, the date and time of the complaint, and the nature of the complaint stored on a single protected server with restricted access. 
The probability of a breach of 311 data is estimated as possible because of its restricted access, location on a single server, and lower frequency of information identifying individuals. As a contrasting example, the probability of a breach of student data is estimated as near certain because of its location, proliferation, access mode, and outdated protection.  For these two examples, the severity of the consequences of a potential breach are both estimated to be major in that the information identifies individuals that could be in compromised situations.   
The results of a qualitative risk assessment allow local governments to tailor specific policies and procedures to specific consequence categories. Considering the example risk matrix in Table 1, governments might require de-identification, anonymization, and/or elimination of sensitive fields before releasing any PII that falls in the darker shaded cells, or cells that define information that demonstrates a higher probability of being breached combined with more severe potential consequences. For example, governments may decide that 311 data can only be released by removing location and time-of-day information. Similarly, governments may require minimal internal review or modifications of data that falls in the lightly shaded cells in Table 4. 
A full attribution of PII on a risk matrix can help local governments prioritize scarce resources. Staff can better detail the sensitivities specific to each data set and prioritize appropriate actions.  For example, simple security measures may significantly mitigate the consequences of PII where the potential consequences are moderate and breach is likely or near certain.; 
It should be emphasized that a thorough qualitative risk assessment can be resource intensive and may be overly burdensome for federal government, particularly where governments administer a limited amount of PII.  While a risk assessment is helpful, it is not a necessary step in reducing the risk of a PII breach.  
Table 1: An example risk matrix.  The rows represent probability categories associated with a potential PII breach. The columns represent variation in the severity of consequences associated with a potential PII breach. The darker shading represents a semi-quantitative assessment of the consequences of a potential breach (consequence = probability × severity). 


####Data Quality Assessment

####Comparison to Other Communities

####De-identification and Anonymization





Some data that contains PII is often released as open data...

###4. Evaluate the Consequences of a PII Breach


 Examining data to identify for quality issues, and validation, and also the degree to which individuals can be uniquely identified in the data if linked to other sources of information. For example, data that contains unstructured information (such as notes fields) can sometimes contain PII. In some cases, data that has been stripped of names can still be linked to other information to identify unique individuals.

The severity of a breach includes potential liability to both individuals and organizations.  The severity are a breach of PII are influenced by the sensitivity of the information. the context in which it is used, and obligations organizations may have to protect the information. Since the selection and definition of severity categories are subjective, staff might openly discuss examples of consequences that meet the various severity criteria. 


###9. Collaborate and Learn from Peers 
Sharing data is not a new phenomenon. Valuable information can be gained by looking at how other organizations share a particular dataset, or what types of policies and practices they've developed.




##Evaluating Harm

###10 Contact the Western Pennsylvania Regional Data Center
The Regional Data Center is here to help your organization responsibly share data. We encourage you to contact us if you have any questions about protecting privacy or sharing data. We also are planning to develop resources and other materials to help you and your organization responsibly manage and share information.


Organize in this way instead of #'s 1-10 

- Evaluation of harm
- Assess data quality
- Data management to prevent accidental release
- Responding to accidental release




##How to Reduce the Risk of Accidentally Releasing PII
There are several actions your organization can take to minimize the risk of accidentally releasing data containing PII or other sensitive information. The information in the publishers guide summarizes more-detailed information presented in UCSUR's 2015 White Paper "Frameworks to Protect Personally Identifiable Information and Assess the Risk of Unintended Breaches"

The probability of a breach related to open data can be minimized by effective information management practices.

###1. Inventory PII
Developing a catalog of the PII is held by the organization can inform internal processes and procedures designed to protect privacy. This inventory can include information about: 
- what type of PII exists
- file structures and formats
-  data is created, managed and used, 
- access and retention policies, and
- applicable laws and policies governing the data.

###2.  Eliminate Unnecessary Collection and Retention of PII
Organizations shouldn't collect PII unless the information is essential. Where feasible, governments can also reduce the risk of a PII breach by eliminating unnecessary copies of data containing PII. 

###3. Develop Information Security Policies and Procedures  
Local governments can reduce the risk of a breach of PII by developing and applying policies and procedures for data security, access, and management throughout the life cycle of data. Additional protections that can be adopted by local governments include developing information retention schedules, storage, and disposal procedures. It's a good practice to document these processes, reference them in matadata, and share them with others in the organization. 



###5. Develop policies and procedures for managing a breach 
Organizations can limit consequences by developing a breach management plan that outlines policies and procedures for managing a breach, and staff that should be involved in the response. Responses to breaches should be proactive, timely, and efficient. The breach management plan can include a timeline of breach responses policies and procedures. If a breach is suspected, the response team should clearly investigate details associated with the breach, including an estimate of the number of individuals potentially affected, the likelihood the information will be used to cause harm, and the severity of the consequences. The breach management plan should also include communication protocols for internal audiences, the media, and individuals that may have been directly affected.  

###6 Create Education and Training Programs
Education and training can help individual staff and the organization take appropriate measures to reduce the risk of a confidentiality breach. Educational materials could include a definition of PII, and a description of applicable privacy laws, regulations, and policies. Training can cover data management plans and practices, and can also address actions to take in response to a breach.

###7. Be Transparent
Sharing information on open data plans and policies can result in valuable feedback to the data publisher. This information can be used to develop publication priorities, educate data users, and enhance efforts to protect privacy.

###8. Establish Periodic Reviews of PII Policies and Procedures
Legal and legislative standards, security controls, information technology, and the information itself will all change over time.  Maintaining effective practices to protect PII will require a commitment to routinely revisiting internal policies and procedures.




