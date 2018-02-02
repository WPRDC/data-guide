# Creating a data dictionary

Once you've created your dataset and loaded the data onto the portal, one important step before publication is adding a data dictionary.

## What is a data dictionary?

Much like a regular dictionary defines words and tells the reader how to use them, a data dictionary explains all the columns (fields) of your data with enough detail that the reader can start using your data.

It lists each field name that appears in the table of data, provides a definition for the field, specifies the type of data in that field (e.g., "string" or "integer"), and gives an example value that could occur in that field.

## Why are data dictionaries important?

Published data often has field names that are deliberately short, and they may wind up being cryptic or unclear, particularly to someone unfamiliar with the topic that the data describes. The field might be "weight", but if the value is 8, the user won't know if the item weighs 8 pounds or 8 kilograms or 8 tons.

Data dictionaries are a simple way to explain such details and make the data you publish more accessible to other people. 

## Suggested formats

We suggest using a five-field data dictionary to define your data's fields.
The fields we recommend are:
    - 'field_name': The name of the field. (Preferably formatted in all lowercase letters and with underscores instead of spaces or other punctuation.)
    - 'type': The type of the field, coded as something like "text" or "float" or "int". The [full list of types for values that go into the CKAN datastore](http://docs.ckan.org/en/latest/maintaining/datastore.html#field-types) (which the WPRDC data portal runs on) is
    > CKAN type | description
    > ----------|------------
    > text | text string
    > int | integer
    > float | real number
    > boolean | a Boolean value (True or False)
    > date | a date without a time
    > time | a time without a date
    > timestamp | a date and a time together (a.k.a., a "datetime")
    > json | a JSON representation of some data (superuseful but by far the most obscure type on this list) 
    
    
    - 'description': A definition of the field (you could, for instance, include in here that the units of the field value are furlongs).
    - 'example': Just a sample value of the field, so that the user knows what it looks like (particularly helpful in case of weird date formats).
    - 'notes': A place to put anything else, including relevant information about how the field might have been calculated from another field or transformed for publication.



The Notes field is a good place to put information that does not fit anywhere else. For instance, if it was necessary to transform ID data from one form to another to get a standardized ID, this could be described in the Notes section documenting that field.

define the raw data itself but instead relates to how the data has been

Other suggestions: We like to name fields by making all the letters lowercase and converting spaces and other punctuation to the underscore character \(\_\). So, we would convert the field name 

## How to create a data dictionary

Option 1: You can use a spreadsheet program and then export the results to CSV.

If you do it this way,check it over by opening it in a text editor, to make sure that Excel didn't format anything (like dates) weirdly.

Option 2: You can type it up by hand. It's not that hard if you have an example.
(See [here](https://github.com/WPRDC/little-lexicographer/tree/master/examples) for examples about books.)

Option 3: Use this handy Python script I wrote: [little-lexicographer](https://github.com/WPRDC/little-lexicographer).


