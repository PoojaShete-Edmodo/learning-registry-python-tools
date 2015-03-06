#Learning Registry Python Extractor

##DESCRIPTION

The Learning Registry Python Extractor provides scripts to submit digital content metadata into the Learning Registry.

##COMPONENTS

* extract.py - Extracts metadata envelopes from the Learning Registry with "lrmi" tags into individual JSON files.  Search parameters can be changed in lines 70-74.

* insert.py - Inserts individual JSON files that are in LRMI JSON-LD format into a schematized MySQL database.

* /sql - MySQL scripts necessary to create database for insert.py


##LICENSING

Learning Registry Python Bulk Publisher is licensed under the Apache License, Version 2.0 by Learning Tapestry, Inc. See LICENSE-2.0.txt for full license text and rights.
