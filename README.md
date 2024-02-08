OCA_README is a human-readable plain text format of an OCA Schema

# Schemas and the OCA format
A schema describes the structure of your data and can contain helpful information such as what kind of data is in each column, what units you are using, a description of each data column and more. If you want to help people understand how to use your data you could provide them with a schema. [Learn more about what a schema is](https://agrifooddatacanada.github.io/OCA_training_pathway/what_is_a_schema.html).

The [Overlays Capture Architecture (OCA)](https://github.com/the-human-colossus-foundation/oca-spec/tree/master/docs/specification) is a way to represent a schema. The advantage of OCA schemas is that they are modular and arranged in a series of overlays that reference a capture base using Self Addressing Identifiers ([SAIDs](https://agrifooddatacanada.github.io/OCA_training_pathway/identifiers_and_saids.html)). You can start with a very simple design, and because of the OCA layered architecture you can add more functionality to the schema later.

# OCA README for humans to read and to archive
Overlays Capture Architecture (OCA) is a machine-readable way to encode a schema expressed in the JSON scripting language. While JSON files are text files, they are not built to be easy for people to understand.

We have created a plain text file representation of all the information in a OCA Schema Bundle. The OCA README file can be opened with plain text viewers such as Notepad in Microsoft Windows. Because of it's simplicity, the OCA README file is very suitable for schema archiving purposes. The OCA README file starts with some citations of the OCA standard and then lists all the overlays present in the bundle in the manifest. After the manifest there is a list of the contents of each overlay. The OCA README contains all the information that is present in the source OCA Schema Bundle.

# How to use OCA README

> OCA Schema Bundle and OCA README complement each other. One is for machines. One is for humans.

When you create a schema such as when using the [Semantic Engine](https://semanticengine.org) you should download and use both the machine-readable OCA Schema Bundle (the .json file) and the human-readable OCA README (the .txt file). Store these files together with your data. When you share your data share both of these files to help users understand the context of your data. If your schema is general enough for others to use you can both schema files in a repository and cite this repository entry. [Learn more about how to save and use your OCA schema files](https://agrifooddatacanada.github.io/OCA_training_pathway/deposit_schema.html).

# How OCA README is generated
The OCA README is auto-generated through the JSON formatted overlays conversion process sourced from the OCA Schema Bundle. The file containing the schema undergoes manipulation to facilitate the generation of the textural format (.txt), employing regular expression techniques (regex).

Example:
meta.json overlay from the OCA Schema Bundle (.zip) converted to text (.txt)

```json
{
  "files": {
    "E0aIw86nmdXW-q_5ZNfG2IYTjVeLlBwlybl25FbNO924": {
      "character_encoding": "ELZ3e5V504NmvpwjVWgxt84n_0NeZJ6yFZJv-sC3_wxY",
      "entry (en)": "EKHu8OX8ZJP4x9wqF1mQy1O1EfMsurw8AV3IP5sjeOoY",
      "entry (fr)": "EQ7psoAh65mHNry7owqnqzSOOXA_oFg2QApyrMOJr4is",
      "entry_code": "EjnqI_clse1DdXz9EDVPu8dg4VV02KZrjBHY5FxuXNKk",
      "format": "Eb2fIhmp_Q5dT7Q8kkWHQkPAokumcVHV0fGFDaVjmWns",
      "information (en)": "Elbm-CJBVequ0J8Ft3UrvfoE02BVyVyaVUvbgC_D2hlk",
      "information (fr)": "EjA9YI2w1R3Nf6OoaRXQYHM91ivkgrXxDz90BAW-Dv6Y",
      "label (en)": "EeE1JZNls0oBEB5txnvZBy1nBIqJdM6xWeqZDvtZV3Sc",
      "label (fr)": "E_JEg7KZ9JLtOouE-phmsSlQYJcO5uct9E0_-AiNZCYs",
      "meta (en)": "Eiyaaxy933pVhwAssIyS57V7Axnj4JiefIo0CJbX4j4U",
      "meta (fr)": "ElVpNjcfXyzqdGel_mOyn4yCnRCIHSap9oIlcOu02bmY",
      "unit": "EfT5v5KWdez0DIVxn1Dqts8E2CIxlci7TXoRPTf1QWX8"
    }
  },
  "root": "E0aIw86nmdXW-q_5ZNfG2IYTjVeLlBwlybl25FbNO924"
}
```

```
BEGIN_OCA_MANIFEST
************************************************************
"capture_base" SAID: "E0aIw86nmdXW-q_5ZNfG2IYTjVeLlBwlybl25FbNO924",
"character_encoding" SAID: "ELZ3e5V504NmvpwjVWgxt84n_0NeZJ6yFZJv-sC3_wxY",
"entry (en)" SAID: "EKHu8OX8ZJP4x9wqF1mQy1O1EfMsurw8AV3IP5sjeOoY",
"entry (fr)" SAID: "EQ7psoAh65mHNry7owqnqzSOOXA_oFg2QApyrMOJr4is",
"entry_code" SAID: "EjnqI_clse1DdXz9EDVPu8dg4VV02KZrjBHY5FxuXNKk",
"format" SAID: "Eb2fIhmp_Q5dT7Q8kkWHQkPAokumcVHV0fGFDaVjmWns",
"information (en)" SAID: "Elbm-CJBVequ0J8Ft3UrvfoE02BVyVyaVUvbgC_D2hlk",
"information (fr)" SAID: "EjA9YI2w1R3Nf6OoaRXQYHM91ivkgrXxDz90BAW-Dv6Y",
"label (en)" SAID: "EeE1JZNls0oBEB5txnvZBy1nBIqJdM6xWeqZDvtZV3Sc",
"label (fr)" SAID: "E_JEg7KZ9JLtOouE-phmsSlQYJcO5uct9E0_-AiNZCYs",
"meta (en)" SAID: "Eiyaaxy933pVhwAssIyS57V7Axnj4JiefIo0CJbX4j4U",
"meta (fr)" SAID: "ElVpNjcfXyzqdGel_mOyn4yCnRCIHSap9oIlcOu02bmY",
"unit" SAID: "EfT5v5KWdez0DIVxn1Dqts8E2CIxlci7TXoRPTf1QWX8"
************************************************************
END_OCA_MANIFEST
```

