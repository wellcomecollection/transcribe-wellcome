---
description: Draft instructions
---

# Checking & importing visual batches

## PHO Registers

* Unhide any hidden columns in the transcription spreadsheet and delete them if they are blank to avoid confusion during the import stage
* Insert a new column for `PHO Prefix` (to the left of `PHO No.`) and fill down the column with the text 'PHO' in each cell
* Insert a new column for `RID#` (to the left of `Date of Accession`)
* Locate (or create) the relevant RID#.csv file for the register you are checking; copy and paste the contents as values into a new tab in the PHO Register transcription spreadsheet. Close the RID#.csv file.
* Add the RID#s to each cell in the RID# column in the transcription spreadsheet, by copying the formula `=IFERROR(VLOOKUP(D2,Sheet1!A:B,2,FALSE),"")` into cell A2 and filling down the column. These will typically be the same numerical values as the PHO number, but there are some exceptions, so this is a necessary step.
* Copy and paste the RID# column as values (i.e. to remove the formula from the cells). Add a filter to this column to check there are no blank cells.
* Carry out the usual spot checks on e.g. date format, accuracy of transcription.&#x20;
* Import the batch into TW Visual Collections table in the usual way, selecting Record ID# as the merge field. The TW database is not very good at guessing which field heading is correct, so you really need to be careful you are selecting the correct field, and some of the field headings in the TW table differ from those used in the spreadsheet:
  * `PHO Prefix` maps to `Visual accession number prefix`
  * `PHO No.` maps to `Visual accession number without prefix`
  * There's no need to import the CC0 licence in each row of the data
* Check an entry or two to make sure the digitised images links are working correctly, that the dating looks correct etc.
