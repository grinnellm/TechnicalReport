# LaTeX files to create DFO Technical Reports

The important components are in the `/Document` folder:

- the LaTeX style file `TechReport.sty`,
- the two (unofficial) DFO logos that appear on the title page, and 
- the BibTeX style file `CJFAS.bst`, which I have adapted from Patrick W Daly's CJFAS style file.

I also included Chris Grandin's batch file `clean.bat` to remove temporary files after running LaTeX in Windows. 

## What you need to do

Generating your own report formatting should be fairly self-explanatory.
You will have to edit the custom commands in the `Variables` section of the example file `Example.rnw`.
Follow the example format for author names etc.
One thing to note regarding the title: write the command `trTitle` as the you want it to appear in the citation.
If you have case sensitive words (e.g., species names) in the title, put them in math mode to prevent two case changes:
the title on the cover page is "Title Case",
and the title on the inside cover page is "ALL-CAPS".
Finally, update the link to your BibTeX file in the `References` section.

## Note

I am not an advanced programmer for LaTeX or BibTeX style files, and I wrote and tweaked these files to write my own Technical Reports.
I am aware that these style fles have ugly cludges; please make suggestions if there are cleaner ways to set up these files.