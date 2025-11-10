# Importing Library batches for WA/HMM/LI/Acc/2

These (as WA/HMM/LI/Acc/1 which is now complete) are extremely straightforward as there are few accession numbers and so no placeholder records to overwrite.

* Import the batch into TW Library Accessions table, selecting Record ID# as the merge field (there are no RID#s for these batches, so in fact TW will create them on import). The spreadsheet needs to be closed before you can open it in TW.
* The TW database is not very good at guessing which field heading is correct, so you really need to be careful you are selecting the correct field:
  * I find it helps to open the spreadsheet again in Excel once you get to the field-by-field Import screen in TW, and to unhide any hidden fields. If you have the columns filtered too, where columns are in fact blank (e.g. location) because they are not used in register 2, there is no need to import these columns into TW - simply select 'Do Not Import' instead.
  * There's no need to import the CC0 licence in each row of the data.
* Check an entry or two on TW to make sure the digitised images links are working correctly, that the dating looks correct etc.
* Save the imported transcription spreadsheet in the relevant 'imported to QB' folders in both Sharepoint locations, and mark the import off as complete on the transcribers' log.
