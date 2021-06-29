---
description: Instructions for preparing new A number batches for flimsy slip boxes
---

# Itemising batches for TW import and catalogue descriptions

{% hint style="success" %}
Complete flimsy slip transcription template with A number sequence within box
{% endhint %}

The ordinary transcription template can be used to itemise A number batches within boxes. Complete the following columns \(only\):

* A number \(without prefix\)
* Image no.
* Old R number
* New R number

{% hint style="success" %}
Import itemised batch into Transcribe Wellcome WHMM records table
{% endhint %}

Remember to split registration number prefixes from numbering in both series before import. Only import complete columns.

{% hint style="success" %}
Extract a string of A numbers from Excel column for adding to catalogue descriptions
{% endhint %}

Select a blank cell adjacent to the list's first data, for instance, the cell B1, and type in this formula \(where A1:A500 are the cells in the column you want convert to comma serrated list and "; " the separator you want to separate the list\):

```text
=CONCAT(TRANSPOSE(A1:A500)&"; ")
```

Highlight the formula and press **F9**

Copy and paste the resulting string into the catalogue description field, editing the beginning and end according to standardised catalogue style. 

