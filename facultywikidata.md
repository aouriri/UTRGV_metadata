Based on the work and [presentation](https://osf.io/r3vfp/) by Elisabeth Shook and Jennifer Hawkins at Boise State University.

## Overview of the Workflow (initial workflow outlined in presentation)
1. Citations collected and stored in [Zotero](https://www.zotero.org/)
2. Authors
  * Scrape names and titles from the faculty directory using [Data Miner](https://dataminer.io/)
  * Download results as XSL file to upload into [OpenRefine](https://openrefine.org/)
  * Use OpenRefine to organize, reconcile, build schema, and upload author data to Wikidata
3. Works
  * Export collections from Zotero associated with faculty name as CSV<sup id="a1">[1](#f1)</sup>
  * Open file in Excel to remove null columns and save as XSL
  * Use OpenRefine to reconcile, create schema, and upload works data to Wikidata

## Questions/issues to consider
  * Refining workflow -- more automation, especially for collecting citations
  * Process for future citation updates -- Google Scholar alerts or scheduled scraping
  * Sharing/training for possible assistants or replacement

## Collecting citations

*NOTES:* Google Scholar scrape versus manually adding citations to Google Scholar's "My Library" by *starring* citations; possibly employing both to suit future skillsets; must determine pros/cons of both methods and the efficacy of each method

### DRAFT - citation collection workflow

#### Python/Beautiful Soup Google Scrape

1. Set up scraping environment
2. Extract useful parts -- title/type (h3), link (a), abstract/description (.gs_rs), author/journal info (.gs_a) 
3. Print all and/or compile to report to export for Zotero -- output to BibTeX, for example; find way to package report into prelabeled (faculty's name) "Collection"
4. Import citations/"collection" into Zotero
5. Refine/enhance information, more than likely using [Zotero plugins](https://www.zotero.org/support/plugins)

#### Starring Citations for My Library

1. Search author (author:"[Author Name]"), may need to refine for disambiguation...may need to run multiple searches (:grimacing:)
2. Star relevant citations
3. Select all citations in "My Library" and choose export option (BibTeX and EndNote options work in Zotero import)
4. Import citations/"collection" into Zotero
5. Refine/enhance information, more than likely using Zotero plugins

### Resources
* [How To Scrape Web Pages with Beautiful Soup and Python 3](https://www.digitalocean.com/community/tutorials/how-to-scrape-web-pages-with-beautiful-soup-and-python-3)
* [Web Scraping Google Scholar Results Using Python and Beautiful Soup](https://www.proxiesapi.com/blog/Web-Scraping-Google-Scholar-Results-Using-Python-and-Beautiful-Soup.php)
* [SAGE Research Methods - Practical Data Management with R (video series, requires academic subscription)](https://methods.sagepub.com/Search/Results)


<b id="f1">1:</b> Q: Why not just create a CSV during scrape or export starred list as a CSV? Why involve Zotero? A: Zotero provides opportunity for structure & enhancement (plugins!), which is very useful for OpenRefine. [↩](#a1)
