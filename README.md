# yaml-to-json
yaml-to-json is a Node.js command-line tool that can parse YAML files and return the data in JSON format.

It allows developers to easily convert YAML files into a structured and easily queriable format, making it simpler to integrate them into their software development workflow.

By converting YAML files to JSON, yaml-to-json allows developers to import and export them as JSON files, which can be easily read and interpreted by other programs and libraries.

This tool is particularly useful for working with large and complex data that is represented in YAML format, as it helps to structure and organize the data in a way that is more manageable and easier to understand.

## Installation
To install yaml-to-json, you will need to have Node.js and npm installed on your machine. Once you have these prerequisites installed, you can install yaml-to-json by running the following command:

`npm install -g yaml-to-json`

This will install yaml-to-json globally, allowing you to use it from any directory on your machine.

## Usage
The yaml-to-json command-line tool has the following options:

-i, --input <input>: Specify the input YAML file to be converted. This option is required.
-o, --output <output>: Specify the output JSON file name. The default value is yaml.json.

## Examples
Here are some examples of using the yaml-to-json tool. To convert a YAML file to JSON format, you can use the following command:

`yaml-to-json -i abc.yaml -o abc.json`

`yaml-to-json --input school.yaml --output school.json`

`yaml-to-json -i library.yaml`

The first command will parse the YAML file in the abc.yaml file to JSON format, and save the resulting JSON file to abc.json. The second example converts the school.yaml file to school.json. The third example converts the library.yaml file to the default output file, yaml.json.