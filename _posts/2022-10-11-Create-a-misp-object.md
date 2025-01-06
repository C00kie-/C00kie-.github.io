---
title: "Cheat sheet: Create a MISP object"
categories: [MISP, cheat sheets]
tags: [MISP, MISP objects, CTI]
---

## Create a MISP object

[See a MISP object example](https://github.com/MISP/misp-objects/blob/main/objects/cookie/definition.json)

### MISP object location:

```
/var/www/MISP/app/files/misp-objects/objects
````

Create a folder with the name of your object. In this folder, create a file *definition.json*

The header must contain the following informations: 

-  UUID
- description and name
- version
- meta-category
- required
- requireOneOf

You object is filled with attributes, here are some examples: 

- description
- misp-attribute
- ui-priority
- disable_correlation
- multiple
- values_list

### Update MISP

Once you have created your object, update MISP.

Go to *Global actions > List Object Templates* and Update Objects

### Validation

To validate your object, run the following script:

```
./jq_all_the_things.sh
./validate_all.sh
````


source: misp-project