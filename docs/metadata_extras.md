After upgrading our data portal to CKAN 2.7, it became possible to easily create new metadata subfields within the 'extras' metadata field for any dataset. This can be done through API calls or through the CKAN web interface (by editing the dataset package).

Below are partial lists of extras metadata fields in use on [https://data.wprdc.org](https://data.wprdc.org):

# WPRDC custom metadata

| field name      | Use                                                                                | Used by       |
| --------------- | ---------------------------------------------------------------------------------- | ------------- |
| last_etl_update | Indicates when the ETL job last finished.                                          | rocket-etl    |
| time_field      | Dict specifying the table field representing the time associated with a row.       | pocket-watch  |
| no_updates_on   | List of days (e.g., "weekends") coding for when a table is not expected to update. | pocket-watch  |
