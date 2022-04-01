---
title: "Interoperable"
teaching: 8
exercises: 0
questions:
- What does interoperability mean?
- What is a controlled vocabulary, a metadata schema and linked data?
- How do I describe data so that humans and computers can understand?
objectives:
- "Explain what makes data and software (more) interoperable for machines"
- "Identify widely used metadata standards for research, including generic and discipline-focussed examples"
- "Explain the role of controlled vocabularies for encoding data and for annotating metadata in enabling interoperability"
- "Understand how linked data standards and conventions for metadata schema documentation relate to interoperability"
keypoints:
- "Understand that FAIR is about both humans and machines understanding data."
- "Interoperability means choosing a data format or knowledge representation language that helps machines to understand the data."
---

> ## For data & software to be interoperable:
> I1. (meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation  
> I2. (meta)data use vocabularies that follow FAIR principles  
> I3. (meta)data include qualified references to other (meta)data
{: .checklist}

## What is interoperability for data and software?

Shared understanding of concepts, for humans as well as machines.

### What does it mean to be machine readable vs human readable?

According to the [Open Data Handbook](http://opendatahandbook.org/glossary/en/):

> *Human Readable*  
> "Data in a format that can be conveniently read by a human. Some human-readable formats, such as PDF, are not machine-readable as they are not structured data, i.e. the representation of the data on disk does not represent the actual relationships present in the data."

> *Machine Readable*  
> "Data in a data format that can be automatically read and processed by a computer, such as CSV, JSON, XML, etc. Machine-readable data must be structured data. Compare human-readable.
> Non-digital material (for example printed or hand-written documents) is by its non-digital nature not machine-readable. But even digital material need not be machine-readable. For example, consider a PDF document containing tables of data. These are definitely digital but are not machine-readable because a computer would struggle to access the tabular information - even though they are very human readable. The equivalent tables in a format such as a spreadsheet would be machine readable.
> As another example scans (photographs) of text are not machine-readable (but are human readable!) but the equivalent text in a format such as a simple ASCII text file can machine readable and processable."


> Software uses community accepted standards and platforms, making it possible for users to run the software.
[Top 10 FAIR things for research software][10FTRS]

[10FTRS]: https://librarycarpentry.org/Top-10-FAIR//2018/12/01/research-software/

## Describing data and software with shared, controlled vocabularies

See
- <https://librarycarpentry.org/Top-10-FAIR//2018/12/01/research-data-management/#thing-8-controlled-vocabulary>
- <https://librarycarpentry.org/Top-10-FAIR//2019/09/06/astronomy/#thing-6-terminology>
- <https://librarycarpentry.org/Top-10-FAIR//2018/12/01/historical-research/#thing-6-controlled-vocabularies-and-ontologies>

## Representing knowledge in data and software

See <https://librarycarpentry.org/Top-10-FAIR//2018/12/01/historical-research/#thing-5-data-structuring-and-organisation>.

### Beyond the PDF
Publishers, librarians, researchers, developers, funders, they have all been working towards a future where we can move beyond the PDF, from 'static and disparate data and knowledge representations to richly integrated content which grows and changes the more we learn." Research objects of the future will capture all aspects of scholarship: hypotheses, data, methods, results, presentations etc.) that are semantically enriched, interoperable and easily transmitted and comprehended.
Attribution, Evaluation, Archiving, Impact
https://sites.google.com/site/beyondthepdf/

Beyond the PDF has now grown into FORCE...
Towards a vision where research will move from document- to knowledge-based information flows
semantic descriptions of research data & their structures
aggregation, development & teaching of subject-specific vocabularies, ontologies & knowledge graphs
Paper of the Future
https://www.authorea.com/users/23/articles/8762-the-paper-of-the-future to Jupyter Notebooks/Stencilia
https://stenci.la/

### Making Metadata Interoperable
- provide machine-readable (meta)data with a well-established formalism
- provide as precise & complete metadata as possible
- look for metrics to evaluate the FAIRness of a controlled vocabulary / ontology / thesaurus
often do not (yet) exist
- clearly identify relationships between datasets in the metadata (e.g. “is new version of”, “is supplement to”, “relates to”, etc.)
- request support regarding these tasks from the repositories in your field of study
for software: follow established code style guides

Examples of Dataste Interoperability:
- Automatic ORCID profile update when DOI is minted
-- DataCite – CrossRef – ORCID


If others can use your code, convey the meaning of updates with SemVer.org (CC BY 3.0)
“version number[ changes] convey meaning about the underlying code” (Tom Preston-Werner)

## Linked Data

[Top 10 FAIR things: Linked Open Data](https://librarycarpentry.org/Top-10-FAIR//2019/09/05/linked-open-data/)

Standards: https://fairsharing.org/standards/
schema.org: http://schema.org/

ISA framework: 'Investigation' (the project context), 'Study' (a unit of research) and 'Assay' (analytical measurement) - https://isa-tools.github.io/

Example of schema.org: rOpenSci/codemetar

Modularity
http://bioschemas.org

codemeta croswalks to other standards
https://codemeta.github.io/crosswalk/

DCAT
https://www.w3.org/TR/vocab-dcat/

Using community accepted code style guidelines such as PEP 8 for Python (PEP 8 itself is FAIR)

Scholix - related indentifiers - Zenodo example linking data/software to papers
https://dliservice.research-infrastructures.eu/#/
https://authorcarpentry.github.io/dois-citation-data/01-register-doi.html

{% include links.md %}
