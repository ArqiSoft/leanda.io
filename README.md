# About Leanda.io

## What is it?

The data is essential for science. Data repositories have existed for decades and have been well-supported by various grants, yet they are merely file stores or highly specialized single-purpose databases.

Leanda.io is an extensible open science data repository. Leanda.io allows users to consume, process, visualize and analyze different data types, formats and data volumes. Its microservice based architecture is designed so that new business domain services can be added without the need to modify the entire system. Currently a large set of modules is implemented providing general content management as well as scientific data handling. Our goal is to address functional, architecture and UX/UX deficiencies of other systems and make Leanda.io the gold standard for the Open Science community. Leanda.io's vision is to be a tool based on open standards for improving data sharing and collaboration with a potential impact across many scientific areas.
There is a clear disconnect between domain-specific databases, publishers’ data repositories and semantic web knowledge-bases. Leanda.io provides a basic data processing pipeline. Leanda.io allows real-time data curation and supports ontologies-based properties assignment with subsequent complex searches. Leanda’s deposition pipeline includes a data mining stage which allows text-mining and data conversion on the fly when a new file is deposited. Leanda.io security model supports private, shared and public data. Leanda.io, by incorporating data mining and a curation pipeline on top of integration with multiple data sources, provides a platform for rapid composition of machine learning training data sets for immediate modeling.

## Data Domains and Formats

Leanda.io supports various formats and is able to convert between them seamlessly at time of import or export. At the moment the following data domain services are in place:

* Generic image files such as PNG, GIF, etc
* PDF files
* Office files (MS Office as well as Open Office are supported)
* Tabular data such as CSV and TSV
* Chemical structures (SDF, MOL etc)
* Chemical reactions (RXN)
* Crystals
* Microscopy files
* Machine learning models

## Machine Learning

A machine learning (ML) framework is embedded into Leanda.io and can be used as an API, standalone tool or can be integrated in a new software as an autonomous module. Leanda.io provides a number of pipelines simplifying data science workflows used in research and drug discovery starting from data import and curation and finishing with the predictive models training, evaluation and application. Trained models can be shared with other users or made public.

## Data Curation and Annotation

Leanda.io was designed to support multiple ways of data acquisition, conversion, real-time automated and manual data curation, annotation and analysis. The system can extract the metadata from the raw files automatically. In addition to automatic metadata extraction Leanda.io provides ways to add hierarchical categories to the data, tag, and to assign additional metadata types.

## Run Locally

The entire Leanda.io system conists of many infrastructure, monitoring and application services. The full system requires quite a lot of resources to run. Especially, the ML services are very resource hungry.

We have created a small lightweight distribution so that people can download and play locally.

To start the system locally please follow these steps:

* Clone <https://github.com/ArqiSoft/configuration> repository.
* Go into `leanda-lite` folder.
* Run `docker-compose up` command.

All you need to install on your machine is the Docker engine. We recommend to allocate 6 GB RAM or more.
