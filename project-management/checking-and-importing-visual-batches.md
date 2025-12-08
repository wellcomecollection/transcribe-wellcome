---
description: >-
  Transcribers should be asked to upload their completed spreadsheets to the
  Transcribers' Teams group. It’s recommended to keep notes on steps 1 and 2 for
  feedback to transcribers.
---

# Checking & importing visual batches

### Step 1. Prepare your batch for checking

1. The file will be saved under the location Documents > General > Checked Pre-Import in the Transcribers' Teams group.
2. Select the file and download it to _your_ local OneDrive. This is the file you will be working with to check - not the copy in the Teams folder.

### Step 2. Double check the returned spreadsheet

1. Unhide any hidden columns in the transcription spreadsheet and delete them if they are blank to avoid confusion during the import stage.
2. Check if there are any empty rows (such as blank slips) and delete them.
3. Select the **`Date of Accession`** field and right click to ‘Format cells’ according to 'Date' and then the long format: DD Month YYYY.
4. Check consistency of **`Date of Accession`** field. Ensure that a date has been entered in every row and that normalisation rules have been applied to the last day of the month where necessary.
5. Step 5 will vary according to the type of register / record transcribed:

#### PHO Registers

* _Either_ insert a new column for **`PHO Prefix`** (to the left of `PHO No.`) and fill down the column with the text 'PHO' in each cell _or,_ if a **`Visual Accession Number Prefix`** column already exists, check the field contains 'PHO' with no blank cells all the way down the column.&#x20;
* Check the **`PHO no.`** field contains a number, with no blank cells.
* Highlight the column for PHO no. and choose **conditional formatting** (in Styles tab). Select H**ighlight cells rules** > D**uplicate values** > OK. Use the filter tab to identify highlighted cells. Check that duplicates and/or sub-numbers are correctly entered in the Sub number field.

#### CC Cards

* Check the **`Visual Accession Number Prefix`** field contains ‘CC’, with no blank cells.
* Check the **`CC number`** field contains a number, with no blank cells.
* Highlight the column for **`CC number`** and choose **conditional formatting** (in Styles tab). Select H**ighlight cells rules** > D**uplicate values** > OK. Use the filter tab to identify highlighted cells. Check that duplicates and/or sub-numbers are correctly entered in the Sub number field.
* Check **`Provisional Classification`** field is correct with only ‘CC’.
* Spot check accuracy of abbreviations in **`Classification`**/**`Present Number`**/**`New Class`**/**`Section`** fields. If it appears there’s a lot of mistakes, check through the relevant documents to check all fields in these columns are in the correct place.
* If needed, merge **`Present Number`** and **`New Class`** fields to a new **`Classification`** field.
  * Insert new column as **`Classification`**
  * In **`Classification`** column, enter the formula relating to the specific cells, e.g. `=IF(G2="",J2,CONCAT(G2,"; ",J2)) (or try =CONCAT(J3,"; ",K3) )`
  * Check the data has correctly merged, and then double click ‘+’ at the bottom right corner of the cell to add all the new data in the cells.
  * Highlight the **`Classification`** column, right click and select ‘copy’. Right click and select ‘Paste options’ – ‘Values (V)’.
  * Filter and delete ‘0’ from any cells, if it appears. Double check the data has merged correctly.
* Check that data in **`Bought of… at`** and **`Auction House`** fields match. Filter the **`Auction House`** field by each auction house and scan against details in **`Bought of…at`** field.
* Scan the **`At Present`** field for any signs of dispersal, transfer or sales. Add details to **`Transcriber’s Notes`** field, e.g. ‘\[Dispersal] Sent to Alford House for Sale’.
* Filter for multiple numbers in the **`Lot No.`** field. Check the relevant Sales Catalogues where possible, and make a note if you’re unable to determine which item is which in the **`Transcriber’s Notes`**.

#### All Transcriptions

6. Check **`Register`** field is correctly entered and includes a slash for WAHMM, e.g. WA/HMM. Check that the register has no blank entries and a correct reference throughout.
7. Use the filter function to check that **`Image no.`** field has no empty entries. If relevant, check it matches correct **`rh image number`** if applicable.
8. If the spreadsheet includes R/P numbers:
   * Insert a new column before **`R/P number`** with **`R/P prefix`**. Insert a new column after **`R/P number`** with **`R/P number`** year. Check through R/P numbers and separate out the data to the new fields.
   * For consistency, add ‘**R**’ to **`R/P prefix`** IF there is no indication as to what the prefix is on the record.
9. Spot check accuracy of abbreviations in **`Classification`** field. If it appears there’s a lot of mistakes, check through the relevant documents to check all fields in these columns are in the correct place.
10. Filter the **`Description of Article`** field to check for ‘ditto’ references. Scan the column in case any records need sub-numbering, e.g. description mentions more than one object.&#x20;
11. Check **`Object Name`** for any blanks and add data if needed. If you’re unsure of an object name, or one is not mentioned on the cabinet card, leave the field blank and add ‘Unsure: Object Name’ to Transcriber’s Notes field if unsure.
12. Check **`Value/Price/Cost`** field has been entered correctly.&#x20;
13. Filter out all blank cells in the **`Remarks`** field, making sure they are additional notes _from the flimsy/register_, and if not, transfer to Transcriber’s Notes column.&#x20;
14. Make sure &#x54;**`ranscriber’s name`**/**`Transcribed by`** field is standardised correctly with the transcriber’s e-mail address and _not_ the name.&#x20;
15. Filter out all the blank cells in **`Transcriber’s Notes`** and check each comment, particularly any 'unsure' notes. Correct where possible.
    * If the transcriber has indicated uncertainty about transcription, check the digitised image and make corrections where you can.
    * Add note to Transcriber’s notes if date has been normalised, e.g. ‘Accession date normalised to last day of entry.’
16. Check **`Sensitivity`** – this should just have ‘Y’ in the box where applicable. Move any other details to Transcriber’s Notes.
17. Use spell check across the spreadsheet for any obvious spelling errors. Through CTRL +F, search for any fields containing ‘ditto’ and update with the relevant details, where necessary.
18. Check and correct vulgar fractions (1/2, 1/4, 3/4 are fine, all others need to be replaced, this includes fractions that have been spelled out and need to be re-typed as numbers).
19. Search for question marks (\~?) for any words that transcribers were unsure of. Add to Transcribers Notes for transcribed question marks.
20. Double check for any non-Latin script and ensure this is transliterated / marked in **`Transcriber's Notes`.**
21. Check and correct any missing tagging on scored-through text through CTRL+F.
22. Check stamps are written as \[stamp].
23. Check the bottom few rows of the sheet, in case additional rows have been added for out-of-place accession numbers. If so, add any missing WA/HMM Box references for these rows, and highlight the rows in a different colour so that they stand out at the next stage.
24. Make sure the assigned batch is transcribed and nothing less or more. If there is a discrepancy, make a note and follow up.
25. Move the spreadsheet into 'Checked Pre-import' folder on the ‘Wellcome Transcribers’ Teams channel

### Step 3. Prepare the spreadsheet for import

6. Insert a new column for **`RID#`** (to the left of `Date of Accession`)
7. Locate (or create) the relevant RID#.csv file for the register you are checking; copy and paste the contents as values into a new tab in the PHO Register transcription spreadsheet. Close the RID#.csv file.

* Add the RID#s to each cell in the RID# column in the transcription spreadsheet, by copying the formula `=IFERROR(VLOOKUP(D2,Sheet1!A:B,2,FALSE),"")` into cell A2 and filling down the column. These will typically be the same numerical values as the PHO number, but there are some exceptions, so this is a necessary step.
* Copy and paste the RID# column as values (i.e. to remove the formula from the cells). Add a filter to this column to check there are no blank cells.
* Carry out the usual spot checks on e.g. date format, accuracy of transcription.&#x20;
* Import the batch into TW Visual Collections table in the usual way, selecting Record ID# as the merge field. The TW database is not very good at guessing which field heading is correct, so you really need to be careful you are selecting the correct field, and some of the field headings in the TW table differ from those used in the spreadsheet:
  * `PHO Prefix` maps to `Visual accession number prefix`
  * `PHO No.` maps to `Visual accession number without prefix`
  * There's no need to import the CC0 licence in each row of the data
* Check an entry or two on TW to make sure the digitised images links are working correctly, that the dating looks correct etc.
* Save the imported transcription spreadsheet in the relevant 'imported to QB' folders in both Sharepoint locations, and mark the import off as complete on the transcribers' log.
