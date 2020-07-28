> From the [bepress Digital Commons "Metadata Options" page](https://www.bepress.com/reference_guide_dc/metadata-options-digital-commons/#metadata-field-basics-in-digital-commons)

**Field components**

* **Field Name:** The back-end field name the system uses, which appears on batch upload and batch revise spreadsheets. This may not be changed after a field has been set up. The field name must be in all lowercase, without spaces, and may not begin with a number. Consulting Services can help you choose a field name that is consistent with the other field names in your repository. Some field names may be in use within the Digital Commons system for system-specific needs and may not be used for metadata fields. If you request a field with one of these names, Consulting Services can help select an alternate field name that is not reserved in the system.
* **Display Label:** The display label for a field is the version seen by users on the submission form and on the record’s metadata page after it is posted. For example, the field with the field name “title” generally has the display label “Title,” and the field with the name “publication_date” generally has the display label “Publication Date.” The display label may be changed for a field at any time.
* **Input Type:** Several options exist to specify which type of input element should be used to capture the data on the submission form. These options may be adjusted for most fields at any time:
  * text: A single-line text box.
  * textarea: A multi-line text box.
  * WYSIWYG: A large text entry box with a set of tools allowing for easy HTML formatting.
  * select: A drop-down list of options, or a multi-select list.
  * fixed: A fixed-value field will not appear on the submission form for either authors or administrators, because it cannot be changed from the default value except in batch revision.
  * checkbox: A small box that is selected with a checkmark when a user clicks on it.
  * radio: Small round buttons that are commonly used for either/or selections.
* **Field Instructions:** Field instructions appear on the submission or revision form below the field title and above the input box. They may contain some HTML, and can be changed for most fields anytime.
* **Field Label:** The field label appears near the input box on a submission form, as shown in the below screenshot. The field label can be changed for most fields at any time.
* **Default Value:** Text fields may contain a default value that is already populated on the submission form when a user loads it. Note that in order for the default value to be saved, it must appear to the user on the submission form, so an editor bypass field (see details below) will not receive default values when authors submit. This setting may be changed for a field at any time.

**Additional field options**

* **Required Status:** Most fields can be either required or optional, and required status may be changed at any time. The Title field is always required.
* **Editor Bypass:** A field that is not editor bypass will appear on the submission and revision form for both administrators and non-administrators. A field that is editor bypass will appear on the submission and revision form only to users logged in as administrators. The editor bypass status may be changed for a field at any time.
* **Displays on Article Information Page:** Each field may be either displayed to the public on article metadata pages, or hidden from metadata pages. The public display setting may be changed for a field at any time.
* **Sort Order:** The sort order determines the order in which fields appear on the submission and revision forms, as well as the order that they appear on public metadata pages. The sort order may be changed for a field at any time.
* **Dublin Core mapping:** Any field may be mapped to a Dublin Core value, or a custom export label. This value will be harvested with particular metadata prefixes through the OAI-PMH interface. To read more about OAI-PMH, see the section on Metadata and OAI Harvesting in this guide, or refer to the document, Digital Commons and OAI-PMH: Harvesting Repository Records. The Dublin Core mapping may be changed for a field at any time.
* **Virtual Collection:** Most fields may be enabled for virtual collection in the repository based on metadata filters. To learn more about the Digital Commons collection tool, please see the document, The Collection Tool: How to Display Submissions in Multiple Publications on Digital Commons.
* **Search Option:** All fields may be searched using the repository’s simple search feature, or by searching “All fields” in advanced search. Several common fields are included by default in the advanced search drop-down menu for narrowing a search. The following additional fields can be added to this list by request:
  * advisor, advisors, advisor1, advisor2, advisor3, other numbered advisor fields
  * department, dept, department1, department2, department3, department4, other numbered department fields
  * grant, grant_num, or grant_number
  * isbn
  * issn
  * major
  * fundref, funder, funding_source
