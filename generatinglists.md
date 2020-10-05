*Step-by-step guide for pulling monthly report of bib records with unlinked LC Names*

This report pulls a list of all bib records that contain unlinked 1xx, 600, 610, 611, 630, 7xx, and 8xx fields.  It should be run on a monthly basis (preferably at the start of the month) for the month prior.
1.	Open the Authority Control Task List by going to **Resources > Cataloging > Authority Control Task List**
2.	Edit the **Submit Date Range** to reflect the month you are interested in
3.	On the left-hand side of the screen under Facets, make the following selections:
  * Vocabulary = **LCNAMES**
  * Suppressed from Discovery = No
  *	Linked to Community Zone = No
4.	Export the list into Excel

*Step-by-step guide for pulling monthly report of bib records with unlinked LC Subject Headings (LCSH)*

This report pulls a list of all bib records that contain unlinked 650 and 651 fields (it also pulls 655 fields as well; since we don't want these we will edit the 655 fields out once the report has been exported into Excel).  It should be run on a monthly basis (preferably at the start of the month) for the month prior.  It's easiest to run immediately after you run the LC Names report as follows:
1.	Click on the “x” next to **LCNames** to remove it from your selections
2.	Go to **Facets > Vocabulary** and select LCSH
3.	Export the list into Excel
