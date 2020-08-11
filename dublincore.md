**Dublin Core Metadata Terms**<sup id="a1">[1](#f1)</sup>

For the digital collections and institutional repository at UTRGV, most of the elements and some qualifiers in Dublin Core are employed. Additionally, [encoding schemes](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-4) such as the Library of Congress Subject Headings [(LCSH)](https://www.loc.gov/aba/publications/FreeLCSH/freelcsh.html), are used implicitly or explictly (see example below) in further describing an object.

![example image of subject headings](docs/subjects-example.JPG)

Properties in the `/elements/1.1/` namespace:

* **contributor:** an entity responsible for making contributions to the resource.
* <a name="coverage" id="cover-id"></a>**coverage:** the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.
* **creator:** an entity primarily responsible for making the resource.
* <a name="date" id="date-id"></a>**date:** a point or period of time associated with an event in the lifecycle of the resource.
* <a name="description" id="desc-id"></a>**description:** an account of the resource.
* **format:** the file format, physical medium, or dimensions of the resource.
* **identifier:** an unambiguous reference to the resource within a given context.
* **language:** a language of the resource.
* **publisher:** an entity responsible for making the resource available.
* **relation:** a related resource.
* <a name="rights" id="rights-id"></a>**rights:** information about rights held in and over the resource.
* **source:** a related resource from which the described resource is derived.
* **subject:** the topic of the resource.
* **title:** a name given to the resource.
* **type:** the nature or genre of the resource.

Properties in the `/terms/` namespace:

* **abstract:** subproperty of [description](#desc-id); summary of the resource.
* **accessRights:**
* **accrualMethod:**
* **accrualPeriodicity:**
* **accrualPolicy:**
* **alternative:**
* **audience:** a class of agents for whom the resource is intended or useful.
* **available:** subproperty of [date](#date-id); date that the resource became or will become available.
* **bibliographicCitation:** a bibliographic reference for the resource.
* **conformsTo:**
* **created:** subproperty of [date](#date-id); date of creation of the resource.
* **dateAccepted:**
* **dateCopyrighted:**
* **dateSubmitted:**
* **educationLevel:**
* **extent:**
* **hasFormat:**
* **hasPart:**
* **hasVersion:**
* **instructionalMethod:**
* **isFormatOf:**
* **isPartOf:**
* **isReferencedBy:**
* **isReplacedBy:**
* **isRequiredBy:**
* **issued:**
* **isVersionOf:**
* **license:** subproperty of [rights](#rights-id); a legal document giving official permission to do something with the resource.
* **mediator:**
* **medium:**
* **modified:**
* **provenance:**
* **references:**
* **relation:**
* **replaces:**
* **requires:**
* **rightsHolder:**
* **spatial:** subproperty of [coverage](#cover-id); identifies a location associated with an item.
* **subject:**
* **tableOfContents:**
* **temporal:** subproperty of [coverage](#cover-id); identifies a time period associated with an item.
* **valid:**

`Elements` specific to Digital Commons

* **thesis.degree:**
* **thesis.degree.discipline**
* **thesis.degree.grantor:**
* **thesis.degree.level:**
* **thesis.degree.name:**



<b id="f1">1:</b> From the [Dublin Core Metadata Initiative (DCMI) Metadata Terms webpage](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-3). [↩](#a1)

**See also** [Dublin Core Elements in Digital Commons](docs/Dublin-Core-Elements-in-Digital-Commons.pdf) for a full list of elements that can be used in Digital Commons (ScholarWorks).
