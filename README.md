# Bug in javafx-maven-plugin

When jlink is enabled,
using this project as a dependency in a subproject,
makes the maven build fail.

To reproduce:
`mvn clean install -Pfails`

A version, without jlink, is working:
`mvn clean install -Pworks`