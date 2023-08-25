OCA_README is a human-readable plain text format of an OCA Schema

# Schemas and the OCA format
A schema describes the structure of your data and can contain helpful information such as what kind of data is in each column, what units you are using, a description of each data column and more. If you want to help people understand how to use your data you could provide them with a schema. [Learn more about what a schema is](https://agrifooddatacanada.github.io/OCA_training_pathway/what_is_a_schema.html).

The Overlays Capture Architecture (OCA) is a way to represent a schema. The advantage of OCA schemas is that they are modular and arranged in a series of overlays that reference a capture base using Self Addressing Identifiers ([SAIDs](https://agrifooddatacanada.github.io/OCA_training_pathway/identifiers_and_saids.html)). You can start with a very simple design, and because of the OCA layered architecture you can add more functionality to the schema later.

# OCA README for humans to read and to archive
Overlays Capture Architecture (OCA) is a machine-readable way to encode a schema expressed in the JSON scripting language. While JSON files are text files, they are not built to be easy for people to understand.

We have created a plain text file representation of all the information in a OCA Schema Bundle (the .zip file containing all the JSON files that make up the schema). The OCA README file can be opened with plain text viewers such as Notepad in Microsoft Windows. Because of it's simplicity, the OCA README file is very suitable for schema archiving purposes. The OCA README file starts with some citations of the OCA standard and then lists all the overlays present in the bundle in the manifest. After the manifest there is a list of the contents of each overlay. The OCA README contains all the information that is present in the source OCA Schema Bundle.

# How to use OCA README

> OCA Schema Bundle (.zip) and OCA README complement each other. One is for machines. One is for humans.

When you create a schema you should download and use both the machine-readable OCA Schema Bundle (the .zip file) and the human-readable OCA README (the .txt file). Store these files together with your data. When you share your data share both of these files to help users understand the context of your data. If your schema is general enough for others to use you can both schema files in a repository and cite this repository entry. [Learn more about how to save and use your OCA schema files](https://agrifooddatacanada.github.io/OCA_training_pathway/deposit_schema.html).

# How OCA README is generated

