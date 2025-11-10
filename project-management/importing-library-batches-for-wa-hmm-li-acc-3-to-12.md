# Importing Library batches for WA/HMM/LI/Acc/3 to /12

* Open the transcription spreadsheet in Excel. Unhide any hidden columns and delete them if they are blank to avoid confusion during the import stage
* Insert a new column for `RID#` (i.e. TW record ID number, to the left of `Date of Accession`)
* Open (or download from TW) the relevant RID#.csv file for the register you are checking. Previously downloaded RID# files can be found in a folder in the main Wellcome Transcribers Group sharepoint Documents > General > Completed spreadsheets > RID#s.&#x20;
* Copy and paste the contents as values into a new tab in the transcription spreadsheet. Close the RID#.csv file.
* Add the RID#s to each cell in the RID# column in the transcription spreadsheet, by copying the formula `=IFERROR(VLOOKUP(C2,Sheet1!A:B,2,FALSE),"")` into cell A2 and filling down the column.
* Copy and paste the RID# column as values (i.e. to remove the formula from the cells). Add a filter to this column to check there are no blank cells.
* Carry out the usual spot checks on e.g. date format, accuracy of transcription.
* Import the batch into TW Library table in the usual way, selecting Record ID# as the merge field. The TW database is not very good at guessing which field heading is correct, so be careful you are selecting the correct field:
  * There's no need to import the CC0 licence in each row of the data
* Check an entry or two on TW to make sure the digitised images links are working correctly, that the dating looks correct etc.
* Save the imported transcription spreadsheet in the relevant 'imported to QB' folders in both Sharepoint locations, and mark the import off as complete on the transcribers' log.

[\
](https://docs.wellcomecollection.org/collections-information/lQ0fMyP8xr8hWWJiQkfl/transcribe-wellcome/project-management/importing-itemisation-batches)
