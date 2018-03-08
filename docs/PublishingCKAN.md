# Publishing on the Regional Data Center's Open Data Portal

This section of the publisher's guide covers the process for manually publishing a dataset to the Regional Data Center's open data portal.

The open data portal used by the Regional Data Center is powered by open source software called CKAN. 


### Before creating a dataset the first time, you'll need to make sure that:

1. You are logged-in to CKAN and your account has the appropriate permissions enabling you to publish
2. Your data file is machine readable and is in an appropriate file format. Refer to the "preparing your data" section of this guide. 
3. You have created a data dictionary for your file. See the "creating a data dictionary" section of this guide.
4. You are prepared to create a metadata record for your dataset. Metadata is created as part of this publishing process. Details in how to do this are included below.

### Before updating an existing resource within the dataset, you'll need to make sure that:

1. You are logged-in to CKAN and your account has the appropriate permissions enabling you to publish data.
2. Your data file is machine readable and is in an appropriate file format. Refer to the "preparing your data" section of this guide.

### Creating a CKAN Account

Creating an account on CKAN involves visiting the [Regional Data Center web site](https://data.wprdc.org/user/register) and entering a user name, password, and email address.

Regional Data Center staff or your organization's administrator will also associate your CKAN acount with the appropriate organization.

### Logging-in to CKAN

To be able to publish a dataset, you must be logged in to the open data portal using your CKAN account. Your account must also be provided with editor or admin priveliges, as described below. To login, please visit the Regional Data Center's [login page](https://data.wprdc.org/user/login).

### Accounts and Roles

Accounts in CKAN can have one of three roles. The roles available within CKAN include:

* member: members can view private datasets owned by their organization, but cannot add data to the site.
* editor: can edit, read and create new objects on CKAN
* admin: admin can do anything including: edit, read, delete, and update permissions (change authorizations for that object)

### Assigning Permissions

All accounts initially created on CKAN lack publishing permissions. To publish data, your account will need to be assigned either an editor or admin role. 

Only the Regional Data Center or the designated CKAN administrator at your organization is able to assign the appropriate role to your account. 

You will need to provide them with your CKAN user name to assign you as an administrator or editor. [Please contact](http://www.wprdc.org/contact/) the Regional Data Center if you have any questions.

A CKAN administrator in your organization ([or WPRDC staff](http://www.wprdc.org/contact/)) will also need to provide your account with permission to add data to topical [categories or groups](https://data.wprdc.org/group) on the web site. The administrator will use the [group adder](https://www.wprdc.org/group-adder/) tool to assign these permissions.  

Within an organization, we'd like there to be a primary point of contact that can coordinate among all publishers within your organization, if applicable.

### Datasets and Resources Defined

* It's best to think of datasets within CKAN as a container that holds information about the dataset itself in a metadata record, along with a number of resources. 

* Resources in CKAN are items within the dataset "container" itself. Resources can include files of many data types within the same dataset, including data file formats, pdf's, images, hyperlinks, and text documents. Resources in the same dataset might contain the data for the same information broken into a separate resource by year, a data dictionary describing the fields in a data table, or a  hyperlink to a dataset or tool hosted in a different location. CKAN accepts data in many different formats. A resource can be in a variety of formats, including (but not limited to): CSV, Excel spreadsheet, text file, JSON, PDF document, JPEG image file, etc. CKAN can store the resource internally or provide a link to resources hosted elsewhere on the web.

### Creating a Dataset

Manually uploading data to CKAN involves a two step process. The first step in the process involves the creation of a dataset. The second involves the uploading of resources. 

To start the process, assuming you're logged-in to CKAN, click on the "Add Dataset" button from the [Dataset](https://data.wprdc.org/dataset) web page:
![alt text](AddDatasetButton.GIF "Add a dataset")


#### Metadata

The first step in the process of creating a dataset involves the creation of a metadata record. Metadata is a structured framework for documenting data. The metadata standard we’re using is largely based on one used by San Francisco and U.S. Data.gov. Were also grateful for advice from Digital Scholarship Services at the University of Pittsburgh

We’ve programmed the open data portal software to automatically complete some of the metadata. We’ve also provided drop-down forms saving you from having to type pre-defined responses where possible.

We also don’t require all of the metadata elements to be completed when data is loaded to the portal. We have a few required fields (as noted below), and more detail can be added to the metadata later.

You may find it convenient to use our [metadata entry worksheet](https://docs.google.com/document/d/1sWZ91Newgov2CAL8hcGMADk2eze8EDon2V4mrUmPf44/edit?usp=sharing) prior to creating a dataset and metadata record on the web site. It will take some planning to gather all necessary materials for the metadata record. If the metadata information is gathered in advance, It may take as littla as five minutes to enter a metadata entry for a dataset. It shouldn’t need to be updated unless some of the details have changed.  

##### Title (Required)
Short human-readable name of the asset. Should be in plain English and include sufficient detail to facilitate search and discovery. Avoid acronyms. Use "title case" spelling, and no need to list dates. Don't include the organization name here.

##### URL
URL link to the dataset landing page on the open data portal. This field is automatically populated by the software.

##### Description (Required)
Provide a longer description of the data (compared to the title) written in plain language that can be readily understood by non-technical users. It's a good practice to include your organization's name in the description 

##### Tags (Required)
Keywords that describe the dataset. Enter separated by semicolons. Acronyms acceptable. Use technical and non-technical terms. Use as many as needed. Use plural forms of the word, and also singular forms if different from plural (i.e. leaf/leaves, wife/wives).

##### License (Required)
License definitions and additional information on licenses can be found on the [Creative Commons web site](https://creativecommons.org/licenses/) and the [Open Definition web site](http://opendefinition.org/licenses/). A [Public Domain Dedication](https://wiki.creativecommons.org/wiki/Public_domain) in lieu of a license is also a choice that will allow for maximum re-use of your data if no copyright is present. This information is entered using a drop-down menu.
 
##### Group/Topic (Required)
The group/topic of the dataset identified by the list of possible values. If a data set can fall into multiple categories, select the one which is most-appropriate. This information is entered using a drop-down menu.

##### Organization (Required)
Name of the organization sharing data. This information is entered using a drop-down menu.

##### Department
Name of the data source department or division (if applicable). This information is entered using a drop-down menu. If no choices are provided, please leave it blank.

##### Access Level
Public datasets are visible to all, and private datasets are only visible to other users in the same organization. New datasets should be set as Private at the time of publication. The Regional Data Center will review the data as a final privacy check, and will set it as Public if no privacy issues are present. This information is entered using a drop-down menu.

##### Public Access Level Comment
An explanation of any general steps that have been taken to make a sensitive dataset public, where appropriate, including obfuscation, aggregation, or anonymization.

##### Temporal Coverage
Start/End periods covered by the data. Separate start and end by a "/". Use years (YYYY), dates (YYYY-MM-DD), or dates and times (YYY-MM-DD"T"HHMMSS). If the data is a snapshot from a particular date or year, please omit the "/".  Examples: 4 digit year range (2013/2015), date range (2011-02-14/2013-07-04), date/time range (2011-02-14T12:00:00Z/2013-07-04T19:34:00Z), 1 year (2015), single date (2/16/2016).

##### Geographic Unit
At what geographic unit is the data collected? For example, if the data is collected by address, it would be Street Address. This information is entered using a drop-down menu.

##### Data Notes
Are there any concerns about overall data reliability? Are there any changes in data collection or methods that the user should be aware of? Are there any constraints with data accuracy? What levels of confidence with this dataset could the user reasonably assume?

##### Related Documents
Related documents such as technical information about a dataset, developer documentation, URL, etc.

##### Frequency - Data Change (Required)
Frequency with which dataset changes. This can be a relative frequency - If the file changes every 1st and 4th Monday, we can code this as bi-monthly, etc. This information is entered using a drop-down menu.

##### Frequency - Publishing (Required)
Frequency with which dataset is published. This information is entered using a drop-down menu.

##### Data Steward Name (Required)
Data Steward's name. Who manages the data and is responsible for making changes to the data? Who understands what the dataset includes and can answer questions about it?

##### Data Steward Email (Required)
Data Steward's email address.

##### We [recorded a video](https://github.com/WPRDC/data-guide/blob/master/docs/Create%20a%20Dataset%20Instructions.gif) to show how the process works...
![alt text](https://github.com/WPRDC/data-guide/blob/master/docs/Create%20a%20Dataset%20Instructions.gif "Add a dataset")

#### Data Dictionary
We also strongly encourage publishers to provide a data dictionary for each data table. Data dictionaries help data users understand the underlying structure of the data file. The data dictionary can be created in a spreadsheet, saved in .csv format, and uploaded to the dataset as a resource. For an example, please see the [example included with the Allegheny County Property Assessment data](https://data.wprdc.org/dataset/property-assessments/resource/d31e1b1c-215d-4693-9898-154ca49050a4). This data dictionary should include (at minimum): 

* name of each field
* description of the data field

The data dictionary can also include information about each field in the data:

* data types (text, numeric, boolean, etc)
* Format (special details related to the format, including currency, decimal placement, dates/times
* Field length (# of characters)
* Unique ID/Primary Key
* Permitted/prohibited values
* Public access limitations

You can read more about data dictionaries, how to make them, and our suggested formats [here](https://github.com/WPRDC/data-guide/blob/master/docs/data_dictionaries.md).

#### Creating a Resource Within a Dataset

The second step in the process involves creating resources within each dataset. The process includes: 

1. Locating the file
2. Naming each resource
3. Providing a description for the resource
4. Specifying the file type

We also [recorded a video](https://github.com/WPRDC/data-guide/blob/master/docs/Create%20a%20Resource%20Instructions.gif) showing how to add a resource for a dataset.

![alt text](https://github.com/WPRDC/data-guide/blob/master/docs/Create%20a%20Resource%20Instructions.gif) "Add a resource")

### Adding a Data View
Coming soon!

### Add Data to Additional Groups

All data published through the open data portal should be assigned to one or more groups. Groups are topical categories that make it easier for users to find information by topical area. On the open data portal, there are 16 groups designated. The primary group assignment for a dataset should be made through the metadata record, however datasets can be assigned to multiple groups if appropriate.

Assigning datasets to additional groups can be done through the groups tab on the dataset "landing page"

### Data Center Privacy Review: Publish New Datasets as Private

The Regional Data Center takes privacy seriously. We require all publishers to understand the privacy implications of data shared through the Regional Data Center. 

More information on handling sensitive data is available in the privacy section of this publisher's guide. 
As one final check, we also require all datasets being published for the first time be marked as "private." Datasets can be published privately through the metadata.

The Regional Data Center will check to see if any datasets are ready for review prior to their going "live" at least once per weekday. If any potential issues are found with the data, you will be contacted by the Regional Data Center. If none are founnd, then Regional Data Center staff will publish your dataset as open data!
We encourage publishers to proactively contact us by phone or email if there are any questions about privacy when publishing a dataset.

When updating resources within a dataset, there is no need to designate the dataset as private unless substantial changes affecting the design or composition of resources within the dataset have been made.

### Editing or Updating a Dataset or Resource

We recorded several additional videos showing how to edit or delete an existing dataset. Links to each video are included below.

###### [Edit a Dataset](https://github.com/WPRDC/data-guide/blob/master/docs/Edit%20a%20Dataset%20Instructions.gif)
###### [Delete a Dataset](https://github.com/WPRDC/data-guide/blob/master/docs/Delete%20a%20Resource%20Instructions.gif)
###### [Add a Resource to an Existing Dataset](https://github.com/WPRDC/data-guide/blob/master/docs/Add%20Resource%20to%20Existing%20Dataset%20Instructions.gif)
###### [Change the File in an Existing Resource](https://github.com/WPRDC/data-guide/blob/master/docs/Change%20the%20File%20in%20a%20Resource%20Instructions.gif)
###### [Reorder a Resource](https://github.com/WPRDC/data-guide/blob/master/docs/Reorder%20Resource%20Instructions.gif)
###### [Delete a Resource](https://github.com/WPRDC/data-guide/blob/master/docs/Delete%20a%20Resource%20Instructions.gif)

### Permanence
Coming soon!

