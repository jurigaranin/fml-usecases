# FHIR mapping language simple use cases

To run the transforms directly from the command line you can use the FHIR Java Validator, [download here](https://github.com/hapifhir/org.hl7.fhir.core/releases/latest/download/validator_cli.jar).

## run the tutorial

Each use case directories:

logical: structurdefinitions

map: Mapping files in FHIR Mapping Language

source: file used to transform

output.json: result of map transform

## Use cases

1. concat - Сoncatenation of first and last name fields from one structure into the fully qualified name field of another structure

2. split - Splitting the full name of one structure into the first and last names in another structure

