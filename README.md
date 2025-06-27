# zotero_styles-for-IJMR_superscript
How to cite a reference using a superscript number in document

To edit the IJMR (or any other Journal of your interest) citation style in Zotero to use superscript instead of brackets, you'll need to modify the CSL (Citation Style Language) file. Here's how you can do it:
Go to Zotero Style Repository if you need to download the style file that you wish to edit.
Open your manuscript file in Word, and open the Zotero Tab.
Open Document Preferences.
Click on Manage Styles, then click on Style Editor.
Copy the CSL code into a a text editor (like Notepad.

To Modify the citation format:
Look for the <citation> section in the CSL file.
Change the citation style to use superscripts by modifying the <layout> section.
Replace <group> tags containing <text variable="citation-number" suffix="]"/> with <text variable="citation-number" font-style="superscript"/>.
Save the Notepad file, then copy/paste the modified style code to the CSL file.
Save your changes to the CSL file.

Test your changes:
Try citing a reference in a document to ensure the numbers appear as superscripts.
style renamed as : indian-journal-of-medical-research-superscript.csl file
