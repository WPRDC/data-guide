# Frequently Asked Questions

**Q:** This dataset is too big for me to work with. How can I download only part of it?

**A:** If there is a tabular view for it, you can filter the Data Table view down to a more manageable number of records if you can pick a category that contains a desired subset of records (e.g., use the MUNICIPALITY field to pick the records for one or two municipalities in the entire county).

1) Above the Data Table, click on the "Add Filter" link. (Data Tables on the landing page of a dataset may not have those link. In this case, find the corresponding data resource under "Data and Resources" and click through to find the filterable Data Table.)
2) A "Select a field" dropdown appears above the "Add Filter" link. Select the field you want to filter on from this dropdown.
3) A new field-values dropdown will be generated below the selected field. Select a value from the dropdown. (For very large tables (millions of records), there may be some delay before the field-values can be gathered and presented in the dropdown.)
4) The Data Table will update, with text to describe the filtered view (e.g., "Showing 1 to 10 of 22,692 entries (filtered from 4,302,279 total entries)"). 
5) You can now sort and browse the filtered view.
6) More importantly, **you can now download the filtered view by clicking the Download button** and then selecting your desired file format.


**Q:** If I'm storing data in an Excel spreadsheet for eventual publication as open data, what Excel data types should I use? For instance, if there are monetary values, should I set the cell type to "Currency" (which adds the dollar sign to the cell value) or as some other type?

**A:** Our preference is to have data uploaded as CSV files. So the question is what the data looks like after it gets saved from Excel as a CSV file. I did a little experiment and found that currency values get exported with a dollar sign; this causes CKAN to interpret them as text fields (not numbers). If you just type them into Excel (without a dollar sign), they pick up Excel's "General" format and then get exported as values that CKAN interpret as numeric values. Also, I note that using Excel's "Number" format truncates decimals to two places.

Excel also does some weird things when handling dates, so please avoid using the "Date" format. If you've got a date to enter, please format the cell as "Text" and enter the date like this: 1776-07-04 for July 4th, 1776. (This still isn't perfect, as CKAN will interpret this as a timestamp and represent it as 1776-07-04T00:00:00.)

One last thing to watch out for: Including commas in numbers (like typing six million as "6,000,000") will cause CKAN to think those numbers are text.

In summary, please format numbers (including monetary values) as "General" and use "Text" for dates.
