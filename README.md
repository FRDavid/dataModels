# FIWARE Data Models

[![MIT license][license-image]][license-url]
[![License](https://licensebuttons.net/l/by/3.0/88x31.png)](https://creativecommons.org/licenses/by/4.0)
[![Documentation badge](https://readthedocs.org/projects/fiware-datamodels/badge/?version=latest)](http://fiware-datamodels.readthedocs.org/en/latest/?badge=latest)
[![Support badge]( https://img.shields.io/badge/support-askbot-yellowgreen.svg)](http://ask.fiware.org)

This repository contains: 
* code that allows to expose different harmonized datasets useful for different applications.
Such datasets are exposed through the [FIWARE NGSI version 2](http://fiware.github.io/specifications/ngsiv2/stable) API (query).
* JSON Schemas and documentation on harmonized datamodels for smart cities, developed jointly with [OASC](http://oascities.org), and other domains. 

This work is aligned with the results of the
[GSMA IoT Big Data](http://www.gsma.com/connectedliving/iot-big-data/) Project.
Such project is working on the harmonization of APIs and data models for fueling IoT and Big Data Ecosystems.
In fact the FIWARE datamodels are a superset of the [GSMA Data Models](http://www.gsma.com/connectedliving/wp-content/uploads/2016/11/CLP.26-v1.0.pdf). 

All the code in this repository is licensed under the MIT License. However each original data source may have a different license.
So before using harmonized data please check carefully each data license.

All the datamodels documented here are offered under a [Creative Commons by Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) License.

## JSON Schemas

We intend to provide a [JSON Schema](http://json-schema.org/) for every harmonized data model. In the future all the
documentation could be generated from a JSON Schema, as it is part of our roadmap. The different JSON Schemas usually
depend on common JSON Schema definitions found at the root directory of this repository. 

There are different online JSON Schema Validators, for instance: [http://jsonschemalint.com/](http://jsonschemalint.com/).
For the development of these schemas the [AJV JSON Schema Validator](https://github.com/epoberezkin/ajv) is being used. For
using it just install it through npm: 

```
    npm install ajv
    npm install ajv-cli
```

A `validate.sh` script is provided for convenience.

Note: JSON Schemas only capture the NGSI simplified representation (`options=keyValues`)

## How to contribute

Contributions should come in the form of pull requests. 

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: LICENSE

## Related Projects 

See:

* [https://github.com/GSMADeveloper/HarmonisedEntityDefinitions](https://github.com/GSMADeveloper/HarmonisedEntityDefinitions)
* [https://github.com/GSMADeveloper/HarmonisedEntityReferences](https://github.com/GSMADeveloper/HarmonisedEntityReferences)
* [schema.org](https://schema.org)
