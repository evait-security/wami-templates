# wami-templates
This repository contains the community maintained files that can be used with the wami command line tool.

# Community Guidelines
Before creating a new YML file for your favorite tool, please make sure that the file follows our guidelines and best practices to keep the data well structured and maintainable.

Make sure that each YML file contains the following variables

- id
- title
- tags
- description
- references
- why_not

All of these fields are mandatory and must be set in order to work with the WAMI CLI interface. The fields are defined as follows:


|field|explanation|
|---|---|
|id|A unique name / slug consisting of only lowercase alphanumeric characters (a-z0-9) and hyphens (-). This id / slug must also be the filename followed by the `.yml` extension|
|title|The real name of the tool / software and maybe a very short description|
|tags|Only lowercase alphanumeric words (a-z0-9) and hyphens (-) are allowed and provided as an array that can be utilized to quickly find the tool without knowing its name or exact function|
|description|A longer text describing the tool and what it does. Be creative and include any words or phrases that will help people find this tool without knowing it|
|references|Links to websites, repositories, or other resources that can help people locate the tool or learn about its capabilities|
|why_not|Alternative programs witch you can use|

Try using one of the following pre-existing file as a template

[nuclei](lake/nuclei.yml)

# Tag stats

TBD
