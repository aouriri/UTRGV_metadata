~~Information on how to generate authority control task list from Alma~~
* Information on how to export list as Excel file
* Information on how to (possibly) reconcile file in MarcEdit or OpenRefine
* Information on how to fix or dismiss records on list after cleaning up list
* Include Excel formulas to assist with clean up; package(s) in OpenRefine to do reconcilation
* Include information from Dan, Dolores, and John about their part in list

The Authority Control Task List provides more details regarding authority record updates and the authority control process that are relevant to the institution's bibliographic record headings.

The Authority Control Task List makes it easier to manage cataloging maintenance tasks. Specifically, this list highlights authority headings updates that require manual intervention. The following is a list of changes highlighted in the Authority Control Task List, some of which may require manual intervention due to a linking issue, a preferred-term-correction issue, or deleted/updated authority record:

* **Linking – Bibliographic heading found no matching authority heading**
* **Linking – Bibliographic heading found multiple matching authority headings (ambiguous)**. This issue may occur as a result of times, for example, when the Library of Congress splits one subject heading into two subject headings such as Nurses and nursing is split and replaced with Nurses and Nursing. It may also occur when the system finds a Community Zone authority record and a local authority record match.
* **Linking – Bibliographic heading linked to an authority record**
* **Linking – Bibliographic heading link changed due to a new authority record replacing an existing authority record (redirection)**. This is for institutions configured for ID-based authority control and that have implemented a Direct ID Prefix in their metadata configuration.
* **Preferred term correction – Bibliographic heading updated**
* **Preferred term correction – Multiple matching AUT headings with same Originating System ID (ambiguous)**
* **Preferred term correction – Bibliographic heading found no authorized term**
* **Authority record deleted – Unlinked the bibliographic heading**
* **Authority record updated**

The Authority Control Task List only goes back 6 months (i.e., it only pulls data from bib records imported in the past 6 months or less and/or data from bib records where corresponding authority records changed in the past 6 months or less)  Thus, *it is essential that Authority Control Task List reports be run on a monthly basis* so that we have a record of historical instances where headings in bib records failed to match.  This enables us to manually fix such instances as time allows.
