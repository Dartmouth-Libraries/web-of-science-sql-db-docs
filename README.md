# Web of Science SQL database documentation

This repository contains documentation for the Web of Science SQL database.

## Generating the documentation
To generate the documentation, create a file `resources/schemaspy.properties` containing the relevant information. You can use `resources/schemaspy-sample.properties` as a template and fill in the missing values.

You can contact [Research Data Services](mailto:researchdatahelp@groups.dartmouth.edu) to obtain the necessary connection info.

With that file in place, run the following command from the repo root (requires a Java Development Kit to be installed, e.g. [openJDK](https://openjdk.org/)):

```bash
java -jar resources/schemaspy-6.2.4.jar -configFile resources/schemaspy.properties
```

The documentation will be generated as an HTML tree in the folder `doc`.

## Accessing the documentation
You can access an [online version of the documentation](https://crispy-bassoon-g6nol8v.pages.github.io/) built from the files in this repository.