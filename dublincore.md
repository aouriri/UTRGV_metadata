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

* **abstract:** summary of the resource.
 * subproperty of [description](#desc-id) (element) and [description](#desct-id) (term)
* **accessRights:** information about who access the resource or an indication of its security status.
 * subproperty of [rights](#rights-id) (element) and [rights](#rightst-id) (term)
* **accrualMethod:** the method by which items are added to a collection.
* **accrualPeriodicity:** the frequency with which items are added to a collection.
* **accrualPolicy:** the policy governing the addition of items to a collection.
* **alternative:** an alternative name for the resource.
 * subproperty of [title](#title-id) (element) and [title](#titlet-id) (terms)
* <a name="audience" id="audit-id"></a>**audience:** a class of agents for whom the resource is intended or useful.
* **available:** date that the resource became or will become available.
 * subproperty of [date](#date-id) (element) and [date](#datet-id) (term)
* **bibliographicCitation:** a bibliographic reference for the resource.
 * subproperty of [identifier](#ident-id) (element) and [identifier](#identt-id) (term)
* **conformsTo:** an established standard to which the described resource conforms.
 * subproperty of [relation](#relat-id) (element) and [relation](#relatt-id) (term)
* <a name="contributor" id="contrt-id"></a>**contributor:** an entity responsible for making contributions to the resource.
 * subproperty of [contributor](#contr-id)
* **coverage:** the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.
 * subproperty of [coverage](#cover-id)
* **created:** date of creation of the resource.
 * subproperty of [date](#date-id) (element) and [date](#datet-id) (term)
* **creator:** an entity responsible for making the resource.
 * subproperty of [creator](#creat-id) (element) and [contributor](#contrt-id) (term)
* <a name="date" id="datet-id"></a>**date:** a point or period of time associated with an event in the lifecycle of the resource.
 * subproperty of [date](#date-id)
* **dateAccepted:** date of acceptance of the resource.
  * subproperty of [date](#date-id) (element) and [date](#datet-id) (term)
* **dateCopyrighted:** date of copyright of the resource.
  * subproperty of [date](#date-id) (element) and [date](#datet-id) (term)
* **dateSubmitted:** date of submission of the resource.
  * subproperty of [date](#date-id) (element) and [date](#datet-id) (term)
* <a name="description" id="desct-id"></a>**description:** an account of the resource.
 * subproperty of [description](#desc-id)
* **educationLevel:** a class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended.
 * subproperty of [audience](#audit-id)
* **extent:** the size or duration of the resource.
 * subproperty of [format](#form-id) (element) and [format](#formt-id) (term)
* <a name="format" id="formt-id"></a>**format:** the file format, physical medium, or dimensions of the resource.
 * subproperty of [format](#formid)
* **hasFormat:**
* **hasPart:**
* **hasVersion:**
* <a name="identifier" id="identt-id"></a>**identifier:**
* **instructionalMethod:**
* **isFormatOf:**
* **isPartOf:**
* **isReferencedBy:**
* **isReplacedBy:**
* **isRequiredBy:**
* **issued:**
* **isVersionOf:**
* **license:** a legal document giving official permission to do something with the resource.
 * subproperty of [rights](#rights-id)
* **mediator:**
* **medium:**
* **modified:**
* **provenance:**
* **references:**
* <a name="relation" id="relatt-id"></a>**relation:**
* **replaces:**
* **requires:**
* <a name="rights" id="rightst-id"></a>**rights:**
* **rightsHolder:**
* **spatial:** identifies a location associated with an item.
 * subproperty of [coverage](#cover-id)
* **subject:**
* **tableOfContents:**
* **temporal:** identifies a time period associated with an item.
 * subproperty of [coverage](#cover-id)
* <a name="title" id="titlet-id"></a>**title:**
* **valid:**

`Elements` specific to Digital Commons

* **thesis.degree:**
* **thesis.degree.discipline**
* **thesis.degree.grantor:**
* **thesis.degree.level:**
* **thesis.degree.name:**



<b id="f1">1:</b> From the [Dublin Core Metadata Initiative (DCMI) Metadata Terms webpage](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-3). [↩](#a1)

**See also** [Dublin Core Elements in Digital Commons](https://aouriri.github.io/UTRGV_metadata/docs/Dublin-Core-Elements-in-Digital-Commons.pdf) for a full list of elements that can be used in Digital Commons (ScholarWorks).
