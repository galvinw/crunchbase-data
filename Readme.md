This data was extracted from the CrunchBase January 2015 dump.  Read more at:
http://info.crunchbase.com/about/crunchbase-data-exports/

By using this data, you agree to follow the CrunchBase Terms of Service and Licensing Policy.

http://info.crunchbase.com/docs/terms-of-service/

http://info.crunchbase.com/docs/privacy-policy/

Included in this repository are CSV exports of the individual worksheets from the Crunchbase Data Export using Excel 2011 Mac.

I dropped removed the analysis pages, removed repeated date columns (month, quarter) and applied consistent date formatting to allow pre-1900 founding dates.

I hope whomever creates these data dumps spends their days crying alone because the pain they cause anyone downstream. It's great to have a data dump, but perhaps a format that supports dates pre-1900, doesn't exports numbers as strings (who doesn't love pretty commas in their numbers) and won't include 20k blank rows and empty columns in an export.  Oh yeah, and leading spaces in a text column can't blame that on Excel? Get your shit together.  Make a machine readable csv, json or (gasp!) SQL-ready dump and people will be much happier.

Until then, I'll keep hand massaging these dumps as required.
