Based on the work and [presentation](https://osf.io/r3vfp/) by Elisabeth Shook and Jennifer Hawkins at Boise State University.

## Overview of the Workflow (initial workflow outlined in presentation)
1. Citations collected and stored in [Zotero](https://www.zotero.org/)
2. Authors
* Scrape names and titles from the faculty directory using [Data Miner](https://dataminer.io/)
* Download results as XSL file to upload into [OpenRefine](https://openrefine.org/)
* Use OpenRefine to organize, reconcile, build schema, and upload author data to Wikidata
3. Works
* Export collections from Zotero associated with faculty name as CSV
* Open file in Excel to remove null columns and save as XSL
* Use OpenRefine to reconcile, create schema, and upload works data to Wikidata

## Questions/issues to consider
* Refining workflow -- more automation, especially for collecting citations
* Process for future citation updates -- Google Scholar alerts or scheduled scraping
* Sharing/training for possible assistants or replacement

Citations collected and stored in Zotero
