# Publishing on CKAN

This section of the publisher's guide covers the process for manually publishing a dataset to the Regional Data Center's open data portal.

The open data portal used by the Regional Data Center is powered by open source software called CKAN. 

### Before creating a dataset the first time, you'll need to make sure that:

1. You are logged-in to CKAN and your account has the appropriate permissions enabling you to publish
2. Your data file is machine readable and is in an appropriate file format. Refer to the "preparing your data" section of this guide. 
3. You have created a data dictionary for your file. See the "creating a data dictionary" section of this guide.
4. You are prepared to create a metadata record for your dataset. Metadata is created as part of this publishing process. For more on metadata, please see the "creating metadata" section of the publisher's guide.

### Before updating an existing resource within the dataset, you'll need to make sure that:

1. You are logged-in to CKAN and your account has the appropriate permissions enabling you to publish data.
2. Your data file is machine readable and is in an appropriate file format. Refer to the "preparing your data" section of this guide.

### Creating a CKAN Account

Creating an account on CKAN involves visiting the Regional Data Center website <https://data.wprdc.org/user/register> and entering a user name, password, and email address.

Regional Data Center staff or your organization's administrator will also associate your CKAN acount with the appropriate organization.

### Logging-in to CKAN

To be able to publish a dataset, you must be logged in to the open data portal using your CKAN account. To login, please visit <https://data.wprdc.org/user/login>

### Accounts and Roles

All accounts initially created on CKAN lack publishing permissions. To publish data, your account will need to have either an editor or admin role. 

Only the Regional Data Center or the designated CKAN administrator at your organization is able to assign the appropriate role to your account. 

You will need to provide them with your CKAN user name to assign you as an administrator or editor.

Accounts in CKAN can have one of three roles. The roles available within CKAN include:

* member: members can view private datasets owned by their organization, but cannot add data to the site.
* editor: can edit, read and create new objects on CKAN
* admin: admin can do anything including: edit, read, delete, and update permissions (change authorizations for that object)

Within an organization, we'd like there to be a primary point of contact that can coordinate among all publishers within your organization, if applicable.

### Datasets and Resources Defined

* It's best to think of datasets within CKAN as a container that holds information about the dataset itself in a metadata record, along with a number of resources. 

* Resources in CKAN are items within the dataset "container" itself. Resources can include files of many data types within the same dataset, including data file formats, PDFs, images, hyperlinks, and text documents. These resources can include a numbr of datasets, a data catalog, reports, etc. 

### Creating a Dataset

Manually uploading data to CKAN involves a two-step process. The first step in the process involves the creation of a dataset. 

#### Metadata

The first step in the process of creating a dataset involves the creation of a metadata record. 
Metadata is a structured framework for documenting data. The metadata standard we’re using is largely based on one used by San Francisco and U.S. Data.gov. Were also grateful for advice from Digital Scholarship Services at the University of Pittsburgh

We’ve programmed the open-data-portal software to automatically complete some of the metadata. We’ve also provided drop-down forms saving you from having to type pre-defined responses where possible.

We also don’t require all of the metadata elements to be completed when data is loaded to the portal. We have a few required fields (as noted below), and more detail can be added to the metadata later.

It should take about 5 minutes to complete a metadata entry for a dataset. It shouldn’t need to be updated unless some of the details have changed.

* Title (Required)
Short human-readable name of the asset. Should be in plain English and include sufficient detail to facilitate search and discovery. Avoid acronyms. Use "title case" spelling, and no need to list dates. Don't include the organization name here.

* URL
URL link to the dataset landing page on the open data portal.

* Description (Required)
Provide a longer description of the data (compared to the title) written in plain language that can be readily understood by non-technical users. It's a good practice to include your organization's name in the description 

* Tags (Required)
Keywords that describe the dataset. Enter separated by semicolons. Acronyms acceptable. Use technical and non-technical terms. Use as many as needed. Use plural forms of the word, and also singular forms if different from plural (i.e. leaf/leaves, wife/wives)

* License (Required)
License definitions and additional information can be found at http://opendefinition.org/
 
* Group/Topic (Required)
The group/topic of the dataset identified by the list of possible values. If a data set can fall into multiple categories, select the one which is most significant. This list will be subject to change on an ongoing basis. The WPRDC will refine this list as we proceed.

* Organization (Required)
Name of the organization sharing data. Must have data deposit agreement with WPRDC

* Department
Name of the data source department or division (if applicable).

* Access Level
Public datasets are visible to all, and private datasets are only visible to other users in the same organization. New datasets should be set as Private to be reviewed prior to being set as Public.

* Public Access Level Comment
An explanation of any steps that have been taken to make a sensitive dataset public, where appropriate, including obfuscation, aggregation, or anonymization.

* Temporal Coverage
Start/End periods covered by the data. Separate start and end by a "/". Use years (YYYY), dates (YYYY-MM-DD), or dates and times (YYY-MM-DD"T"HHMMSS) Examples:4 digit year (2013/2015), Date (2011-02-14/2013-07-04), Date/Time (2011-02-14T12:00:00Z/2013-07-04T19:34:00Z)

* Geographic Unit
At what geographic unit is the data collected? For example, if the data is collected by address, it would be Street Address.

* Data Notes
Are there any concerns about overall data reliability? Are there any changes in data collection or methods that the user should be aware of? Are there any constraints with data accuracy? What levels of confidence with this dataset could the user reasonably assume?

* Related Documents
Related documents such as technical information about a dataset, developer documentation, etc.

* Frequency - Data Change (Required)
Frequency with which dataset changes. This can be a relative frequency - If the file changes every 1st and 4th Monday, we can code this as bi-monthly, etc.

* Frequency - Publishing (Required)
Frequency with which dataset is published.

* Data Steward Name (Required)
Data Steward's name. Who manages the data and is responsible for making changes to the data? Who understands what the dataset includes and can answer questions about it?

* Data Steward Email (Required)
Data Steward's email address.






Link or embed screen capture

#### Creating a Resource Within a Dataset

The second step in the process involves creating resources within each dataset.

Link or embed screen capture

- creating views


### Add data to groups

All data published through the open data portal should be assigned to one or more groups. Groups are topical categories that make it easier for users to find information by topical area. On the open data portal, there are 16 groups designated. The primary group assignment for a dataset should be made through the metadata record, however datasets can be assigned to multiple groups if appropriate.

Assigning datasets to additional groups can be done through the groups tab on the dataset "landing page"

Link or embed screen capture

### Data Center Privacy Review: Publish New Datasets as Private

The Regional Data Center takes privacy seriously. We require all publishers to understand the privacy implications of data shared through the Regional Data Center. 

More information on handling sensitive data is available in the privacy section of this publisher's guide. 
As one final check, we also require all datasets being published for the first time be marked as "private." Datasets can be published privately by...
The Regional Data Center will check to see if any datasets are ready for review prior to their going "live" at least once per weekday. If any potential issues are found with the data, you will be contacted by the Regional Data Center. If none are founnd, then Regional Data Center staff will publish your dataset as open data!
We encourage publishers to proactively contact us by phone or e-mail if there are any questions about privacy when publishing a dataset.

When updating resources within a dataset, there is no need to designate the dataset as private unless substantial changes affecting the design or composition of resources within the dataset have been made.

### Permanence
See LA Publishing guide

### Editing or updating a dataset

Link or embed screen capture

## Setting up an ETL job

ETL (Extract-Transform-Load) jobs are automated processes we create to ingest data from an external source (such as an FTP server or a web site) and convert it into records in a dataset on our CKAN data portal.

This is the typical workflow for creating an ETL job:

1. Using the instructions above, create a dataset (CKAN calls it a "package"), keeping it in "Private" mode.
2. Fill out as much of the metadata as you can, but definitely add a title, description, tags, license, the frequency of data change and publishing, and the data steward name and e-mail address.
3. Upload each of the files that should be in the dataset (these files will eventually be overwritten by ETL processes, but uploading the files lets you set the names and formats of the resources, and provide descriptions if warranted).
4. Read [Creating a data dictionary](https://github.com/WPRDC/data-guide/blob/master/docs/data_dictionaries.md) and then create a data dictionary. For datasets with CSV files (or other tabular data), you don't need to upload a separate data dictionary file now that we have the integrated data dictionaries described in that link.
5. Let our Data Magician know where to find the data (e.g., the file named "awesome_dragons_and_bathtubs.csv" on the FTP server), whether it's an incremental update (e.g., just the last month) or a dump of the entire history, and when the script is scheduled to push new data (e.g., every Monday at 2am).
6. We'll set up the ETL job and let you know. When everyone is satisfied that the dataset is done, someone (you or us) will switch it from "Private" to "Public".
