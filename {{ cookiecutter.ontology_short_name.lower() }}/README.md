# {{ cookiecutter.ontology_short_name.upper() }}: {{ cookiecutter.ontology_long_name }}

Developing a common ontology for the domain of this domain.

*This repository was created using the (ontology cookiecutter)[https://github.com/open-ontology-community/cookiecutter-ontology]*

## Scope

*Define your ontology's scope here*

## Contributing

If you want to learn how you can contribute to {{ cookiecutter.ontology_short_name.upper() }}'s development, please refer to (our contribution manual)[CONTRIBUTING.md].

## License / Copyright / Citation

This repository is licensed under `CC0 1.0 Universal (CC0 1.0) Public Domain Dedication`.
For a scientific citation please see the [CITATION.cff](CITATION.cff).

To cite a specific class of the ontology and its definition please use the following convention:
> 'class label' (FUll-URI) from the [{{ cookiecutter.ontology_long_name }} ({{ cookiecutter.ontology_short_name }})]({{ cookiecutter.ontology_iri }})

## Releases and installation

The latest version of the {{ cookiecutter.ontology_short_name.upper() }} can be accessed at {{ cookiecutter.ontology_iri }}. <br>

The source code of the ontology is found in the folder `src/ontology/` <br>
The main file is `src/ontology/{{ cookiecutter.ontology_short_name.lower() }}.ttl` <br>

All own modules are collected in the folder `src/ontology/edits/`, imported modules are under `src/ontology/imports/` <br>

We recommend to use the software [Protégé](https://protege.stanford.edu/) to open and edit the ontology.

## Teams

*List different teams that work on your ontology.*