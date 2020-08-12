**Dublin Core Metadata Terms**<sup id="a1">[1](#f1)</sup>

For the digital collections and institutional repository at UTRGV, most of the elements and some qualifiers in Dublin Core are employed. Additionally, [encoding schemes](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-4) such as the Library of Congress Subject Headings [(LCSH)](https://www.loc.gov/aba/publications/FreeLCSH/freelcsh.html), are used implicitly or explictly (see example below) in further describing an object.

![example image of subject headings](docs/subjects-example.JPG)

Properties in the `/elements/1.1/` namespace:

* <a name="contributor" id="contr-id"></a>**contributor:** an entity responsible for making contributions to the resource.
* <a name="coverage" id="cover-id"></a>**coverage:** the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.
* <a name="creator" id="creat-id"></a>**creator:** an entity primarily responsible for making the resource.
* <a name="date" id="date-id"></a>**date:** a point or period of time associated with an event in the lifecycle of the resource.
* <a name="description" id="desc-id"></a>**description:** an account of the resource.
* <a name="format" id="form-id"></a>**format:** the file format, physical medium, or dimensions of the resource.
* <a name="identifier" id="ident-id"></a>**identifier:** an unambiguous reference to the resource within a given context.
* <a name="language" id="lang-id"></a>**language:** a language of the resource.
* <a name="publisher" id="publi-id"></a>**publisher:** an entity responsible for making the resource available.
* <a name="relation" id="relat-id"></a>**relation:** a related resource.
* <a name="rights" id="rights-id"></a>**rights:** information about rights held in and over the resource.
* <a name="source" id="srce-id"></a>**source:** a related resource from which the described resource is derived.
* <a name="subject" id="subj-id"></a>**subject:** the topic of the resource.
* <a name="title" id="title-id"></a>**title:** a name given to the resource.
* <a name="type" id="type-id"></a>**type:** the nature or genre of the resource.

Properties in the `/terms/` namespace:

* **abstract:** subproperty of [description](#desc-id); summary of the resource.
* **accessRights:** subproperty of [rights](#rights-id); information about who access the resource or an indication of its security status.
* **accrualMethod:** the method by which items are added to a collection.
* **accrualPeriodicity:** the frequency with which items are added to a collection.
* **accrualPolicy:** the policy governing the addition of items to a collection.
* **alternative:** subproperty of [title](#title-id); an alternative name for the resource.
* **audience:** a class of agents for whom the resource is intended or useful.
* **available:** subproperty of [date](#date-id); date that the resource became or will become available.
* **bibliographicCitation:** a bibliographic reference for the resource.
* **conformsTo:** subproperty of [relation](#relat-id); an established standard to which the described resource conforms.
* **contributor:** subproperty of [contributor](#contr-id);
* **coverage:** subproperty of [coverage](#cover-id);
* **created:** subproperty of [date](#date-id); date of creation of the resource.
* **creator:** subproperty of [creator](#creat-id); 
* <a name="date" id="datet-id"></a>**date:** subproperty of [date](#date-id);
* **dateAccepted:** subproperty of [date](#date-id) and [date](#datet-id);
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

**See also** [Dublin Core Elements in Digital Commons](https://aouriri.github.io/UTRGV_metadata/docs/Dublin-Core-Elements-in-Digital-Commons.pdf) for a full list of elements that can be used in Digital Commons (ScholarWorks).
