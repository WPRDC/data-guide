# Protecting Privacy

## Introduction
Open data publishing requires policies, procedures, and actions to protect individuals and organizations from unintentional sharing of personally identifiable information (PII). In some cases, sharing data including PII can cause people serious harm. The proliferation of digital public records, data contained in social media, inadequate policies for managing and protecting PII, and inconsistent data management practices increase the likelihood that PII can be combined across multiple sources to uniquely identify an individual. This section of the guide is designed to help publishers identify PII, and take steps to minimize the risk and harm of a breach. 

The Western Pennsylvania Regional Data Center is NOT equipped to offer legal advice or opinions related to data sharing. We encourage organizations with questions to contact appropriate counsel with any questions related to the legal aspects of data sharing. 

As a final check, we ask all publishers to mark a dataset as "private" the first time it is shared. We will provide a timely review and publish the data if we have no privacy concerns. If we see something that may cause a risk, we will contact you to discuss any privacy issues that may exist in your data, and work with you to minimize risks where possible.

## What is Personally Identifiable Information (PII)?
Personally identifiable information (PII) is “information about a person that contains some unique identifier, including but not limited to name or Social Security Number, from which the identity of the person can be determined.” [GSA 2014] This description includes both information that directly identifies an individual, such as a name, and information, such as race or gender, that can identify individuals when combined with other information.

The list below describes what might be considered personally identifiable information (PII). It is not meant to be exhaustive but is intended to provide examples and context as to what might be considered PII. 
 
|Personal Identifiers|   
|---------------------|
|Name |
|Social Security number|
|Driver's licence number|
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

## What are Public Agencies Required to Share?
Public records in Pennsylvania are subject to the presumption of openness standard in the Commonwealth’s Right-to-Know Law. This standard dictates that all records are presumed to be open to the public unless:
1. Disclosure is prohibited by law, regulation, or judicial order; 
2. Disclosure is prohibited by privilege, such as attorney-client or doctor-patient privileges; 
3. The requested information meets one of 30 criteria outlined in Section 708 in Pennsylvania’s Right-to-Know Law 
4. AND agencies deem the risks of public disclosure outweigh the benefits. (check on this)

The presumption of openness standard places the burden of proof on agencies to demonstrate any exemption criteria are met. 
Most of the exemption criteria in Section 708 are related to the release of PII, drafts of internal documentation, or records that would pose public risks if released.  It should be emphasized that public agencies can release information that meet the Section 708 exemption criteria if they deem such release in the public’s best interest.  

Additional information about Pennsylvania’s Right-to-Know Law, including a list of Section 708 exemptions, can be found at http://panewsmedia.org/legal/openrecords.

In addition to Right-to-Know laws, individuals may have certain rights to access or be aware of information that pertains to them.  

## Privacy Review Process

#### Assessing Harm of a Release 

The process for identifying the privacy risk in sharing a dataset as open data involves an assessment of the severity of harm that may befall a person from a data release, and an assessment of how probable it is that the release of data will cause harm. This assessment of probability should not be done in isolation. It must also account for harm that may occur if the dataset being assessed is linked to other datasets.  

In its Guide to Protecting the Confidentiality of Personally Identifiable Information (2010), the National Institute of Standards and Technology (NIST) describes three impact levels that describe the harm that may befall people as a result of distributing data containing PII.

* LOW impact means that an individual may face an inconvenience, such as having to change a phone number. 

* MODERATE impacts can include monetary loss due to identity theft, discrimination, denial of benefits, and possible blackmail. 

* HIGH impacts include "serious physical, social, or financial harm, resulting in potential loss of life, loss of livelihood, or inappropriate physical detention." (NIST 2010)

When assessing the harm of a potential data release, it's important to give special consideration of harm that may occur to vulnerable populations, including those who may be at elevated risk of becoming a crime victim. These populations can include children, older adults, victims of violent crime, those under protection from abusers, crime witnesses, informants, first responders, and those that may be targeted because of their race, gender preferences, or sexual orientation.

#### Comparison to Other Communities
Valuable guidance can be gained from other organizations' policies and practices for publishing open data. The Federal government's open data repository (www.data.gov) contains a very large catalog of open data sets shared by Federal, state, and local governments. Using this data catalog, publishers can quickly see how other government agencies handle privacy issues related to datasets similar to your own. While this information should not take the place of a privacy investment, it can be helpful in informing your approach. 

#### Legal Obligations and Review

In some cases, PII protections are defined by law or regulation. Names of political campaign donors often must be publicly released, whereas regulations like HIPAA and FERPA restrict the release of PII by law. To ensure that data they release is not going to violate these or other federal, state, and local ordinances, Some organizations that share open data also incorporate a legal review as part of the privacy review process. This review can provide an important check to determine that data sharing does not violate federal, state, or local privacy legislation and policies, or present undue harm to individuals that may be identified through the data. Even if your organization does not have the resources to submit all datasets for a legal review, granting additional people within the organization with the responsibility to provide an independent review can provide a final check that may prevent the unintended release of PII.

#### Scenario Walk-Through
It's often helpful to walk through scenarios to identify the potential harm that may result from a data release. We encourage making this scenario development a group effort by including other members of your organization in this process. Several questions can guide your organization in this exercise, including:

* Is there any PII included in this dataset? If so, what type of information is included?
* Can this dataset be linked to other data (public or private) to reveal PII? 
* What types of harm might be caused by release of this data, if any?
* If harm can be caused by our releasing this data, is the impact LOW, MODERATE, or SEVERE?

## Reducing Risk Through Deidentification and Anonymization Processes

The presence of protected PII in a database need not pose an insurmountable barrier to the release of data. De-identifying and anonymizing information may be appropriate methods for reducing the risk associated with replicated or retained PII. De-identification involves applying replicable algorithms that remove or obscure any PII such that the de-identified information cannot be used to identify an individual.  The algorithm used for de-identification should be maintained in a location separate from the respective data with appropriate safeguards and access controls. In de-identification, the de-identification algorithm can be used to reconstitute the original PII from de-identified data. 

In contrast, anonymized information cannot be used to reconstitute the original, individual methods. Anonymization methods include generalization (grouping records by category or geographic area), suppressing data, or introducing noise by swapping values of individuals fields or replacing individual values with summary statistics. While PII is removed, anonymized data are often less useful for research and decision support.     

## How to Reduce the Risk of Accidentally Releasing PII or Other Sensitive Information
There are several actions your organization can take to minimize the risk of accidentally releasing data containing PII or other sensitive information. The information in the publishers guide summarizes more-detailed information presented in UCSUR's 2015 White Paper "Frameworks to Protect Personally Identifiable Information and Assess the Risk of Unintended Breaches"

#### Data Quality Assessment

After an organization decides to share information as open data, and has determined that release will cause minimal harm to any individual, a data quality assessment should be undertaken. Every dataset that is shared as open data should be rigorously evaluated before publication to ensure that sensitive information is not being inadvertently shared. It's also worthwhile testing processes used for data de-identification or anonymization.

Several red flags to look for include: 

* Unstructured or semi-structured fields, such as notes fields. These may contain PII, and should be removed before the data is shared as open data.

* Fields with inconsistent content that may have been caused by errors caused in manipulating the data such as sorting, copy/paste, etc. 

#### Inventory PII
Developing a catalog of the PII is held by the organization can inform internal processes and procedures designed to protect privacy. This inventory can include information about: 
- what type of PII exists
- file structures and formats
-  data is created, managed and used, 
- access and retention policies, and
- applicable laws and policies governing the data.

#### Eliminate Unnecessary Collection and Retention of PII
Organizations shouldn't collect PII unless the information is essential. Where feasible, governments can also reduce the risk of a PII breach by eliminating unnecessary copies of data containing PII. 

#### Develop Information Security Policies and Procedures  
Local governments can reduce the risk of a breach of PII by developing and applying policies and procedures for data security, access, and management throughout the life cycle of data. Additional protections that can be adopted by local governments include developing information retention schedules, storage, and disposal procedures. It's a good practice to document these processes, reference them in metadata, and share them with others in the organization. 

#### Develop policies and procedures for managing a breach 
Organizations can limit consequences by developing a breach management plan that outlines policies and procedures for managing a breach, and staff that should be involved in the response. Responses to breaches should be proactive, timely, and efficient. The breach management plan can include a timeline of breach responses policies and procedures. If a breach is suspected, the response team should clearly investigate details associated with the breach, including an estimate of the number of individuals potentially affected, the likelihood the information will be used to cause harm, and the severity of the consequences. The breach management plan should also include communication protocols for internal audiences, the media, and individuals that may have been directly affected.  

#### Create Education and Training Programs
Education and training can help individual staff and the organization take appropriate measures to reduce the risk of a confidentiality breach. Educational materials could include a definition of PII, and a description of applicable privacy laws, regulations, and policies. Training can cover data management plans and practices, and can also address actions to take in response to a breach.

#### Be Transparent
Sharing information on open data plans and policies can result in valuable feedback to the data publisher. This information can be used to develop publication priorities, educate data users, and enhance efforts to protect privacy. 

#### Establish Periodic Reviews of PII Policies and Procedures
Legal and legislative standards, security controls, information technology, and the information itself will all change over time.  Maintaining effective practices to protect PII will require a commitment to routinely revisiting internal policies and procedures.

## Contact the Western Pennsylvania Regional Data Center for Help
The Regional Data Center is here to help your organization responsibly share data. We encourage you to contact us if you have any questions about protecting privacy or sharing data. We also are planning to develop resources and other materials to help you and your organization responsibly manage and share information.
