# Extraction and preparation of chemical information

This organization hosts repositories for the **Extraction and preparation of chemical information** course.

The course focuses on building publication-ready chemical and biological datasets from distributed scientific sources: papers, supplementary files, databases, web resources, repositories and aggregators.

The final outcome of the course is a structured dataset repository with source metadata, extraction artifacts, documentation, validation rules, license information and citation metadata.

## Course goal

Students learn how to move from a scientific data collection task to a reusable dataset.

Each final project should answer four core questions:

- what counts as one dataset record;
- where the data can be found;
- how the data was extracted;
- how the final dataset was cleaned, documented and prepared for publication.

## Data collection pipeline

Each student project follows the same general pipeline:

```text
research task
↓
record definition and dataset schema
↓
source map
↓
PDF extraction
↓
web extraction
↓
cleaning and normalization
↓
final dataset
↓
documentation, license and publication
```

The repository should preserve not only the final table, but also the reasoning and artifacts behind it: source lists, extraction notes, intermediate files, schema decisions, conflict resolution notes and limitations.

## Five course practices

### Practice 1. Record definition and dataset schema

Goal: define what one dataset record is and design the initial dataset structure.

Students define:

- the scientific task;
- the unit of one record;
- main entities and identifiers;
- expected fields;
- required and optional fields;
- preliminary data types;
- examples and non-examples of records.

### Practice 2. Source map

Goal: identify all possible sources that may contain relevant records.

Source map:

- scientific papers;
- supplementary materials;
- databases;
- aggregators;
- web pages;
- APIs;
- GitHub repositories;
- public datasets and benchmarks.

For each source, students document source type, URL or DOI, access date, expected data content, metadata availability, license information, possible overlap and expected conflicts.

### Practice 3. Extraction from PDF sources

Goal: extract data from scientific papers and supplementary PDF files.

Students practice:

- extracting text from PDFs;
- extracting tables;
- identifying useful figures and plots;
- using regular expressions and manual checks;
- preserving links between extracted records and source documents;
- documenting uncertain or ambiguous extraction cases.

### Practice 4. Extraction from web sources

Goal: extract records from web pages, online databases and structured web resources.

Students practice:

- inspecting HTML structure;
- extracting tables from web pages;
- parsing pages with Python tools;
- using requests where appropriate;
- working with simple API-like endpoints when available;
- documenting access rules and limitations.

### Practice 5. Cleaning, normalization and publication

Goal: assemble a publication-ready dataset repository.

Students perform:

- merging records from PDF and web sources;
- cleaning column names and values;
- normalizing units, identifiers and names;
- resolving duplicates and conflicts;
- validating the dataset against the schema;
- writing dataset documentation;
- choosing or justifying a license;
- preparing citation metadata.


## Final exam

The final exam is the complete version of the dataset project developed throughout the course.

It combines the results of all five practices into one coherent repository: dataset design, source mapping, PDF extraction, web extraction, and final cleaning, normalization and publication. The project is evaluated as a whole, with attention to the consistency between the research task, record definition, sources, extracted data, schema, documentation, validation rules, license and final published dataset.

By the end of the course, each student should submit a complete dataset repository that can be reviewed as a publication-ready data project.
