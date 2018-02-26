Frequently Asked Questions

Q: If I'm storing data in an Excel spreadsheet for eventual publication as open data, what Excel data types should I use? For instance, if there are monetary values, should I set the cell type to "Currency" (which adds the dollar sign to the cell value) or as some other type?

A: Our preference is to have data uploaded as CSV files. So the question is what the data looks like after it gets saved from Excel as a CSV file. I did a little experiment and found that currency values get exported with a dollar sign; this causes CKAN to interpret them as text fields (not numbers). If you just type them into Excel (without a dollar sign), they pick up Excel's "General" format and then get exported as values that CKAN interpret as numeric values. Also, I note that using Excel's "Number" format truncates decimals to two places.

Excel also does some weird things when handling dates, so please avoid using the "Date" format. If you've got a date to enter, please format the cell as "Text" and enter the date like this: 1776-07-04 for July 4th, 1776. (This still isn't perfect, as CKAN will interpret this as a timestamp and represent it as 1776-07-04T00:00:00.)

One last thing to watch out for: Including commas in numbers (like typing six million as "6,000,000") will cause CKAN to think those numbers are text.

In summary, please format numbers (including monetary values) as "General" and use "Text" for dates.
