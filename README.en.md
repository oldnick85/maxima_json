# maxima_json

## Description

Computer algebra system module [MAXIMA](https://maxima.sourceforge.io/) 
for serialization and deserialization to [JSON](https://www.json.org/).

## Usage

Just include the **json.mac** module and use the **to_json** and **from_json** functions.

## TODO

 * Add comments to code.

 * Currently, not all special characters in string values are processed.

 * So far, only whole decimal numbers are supported.
 
 * In addition to the main functions (**to_json** and **from_json**), 
   auxiliary functions are created that will be visible when the module is imported. 
   It is necessary either to limit their scope, or to embed them in the main ones.