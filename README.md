# Spring Multi Module Maven Project

To build the project

Format the code according the Spring formatting standard

```shell
./mvnw spring-javaformat:apply
```

And then build the code
```shell
./mvwn clean package
```

To generate the reference documentation, run the following commands:
```shell
./mvnw javadoc:aggregate
cd spring-project-docs
../mvnw site
```

You can view the AsciiDoc here, execute the command in the spring-project-docs directory.

```shell
firefox target/asciidoc/index.html
```


