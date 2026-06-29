**GOOGLE FORM RESPONSE EMAIL SUMMARY**

by pftq

This is a simple script for all new responses to a Google Form to be emailed to the form owner.  

To use this:
1) open the spreadsheet tied to your Google Form and click Extensions > Apps Script.
2) Then paste the script code there and save.
3) Go to Triggers > Add Trigger
4) Choose onFormSubmit, Event source "From spreadsheet", Event type "On form submit"
5) The first time it runs, it'll generate an error in Execution that you need to click into to grant permission.  If you want to skip this step, you can also hardcode the recipient email in the script.
