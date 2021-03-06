[![Build Status](https://travis-ci.org/dhis2/dhis2-docs.svg?branch=master)](https://travis-ci.org/dhis2/dhis2-docs)
This is the DHIS2 documentation project. 

To build the documents, consult the <a href="https://www.dhis2.org/doc/snapshot/en/implementer/dhis2_documentation_guide.pdf">DHIS2 documentation guide</a> for details. 

Otherwise, just execute
```bash
mvn clean package
```
to build the documentation.

If you want to build your own custom documentation, just modify the main pom.xml to suit your needs and then execute

```bash
mvn -f nameOfPom.xml package
```

where nameOfPom.xml is your custom pom.

For further information, contact the groups mailing list at
https://launchpad.net/~dhis2-documenters
