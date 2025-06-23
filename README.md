# Spring-Boot-Learn

#### Maven Key Concepts

* POM file: Project Object File
* To add dependencies - we need **GAV** - GroupId, ArtifactId, Version number
* Example:

  `<parent>`  
  `<groupId>org.springframework.boot</groupId>`  
  `<artifactId>spring-boot-starter-parent</artifactId>`  
  `<version>3.5.3</version>`  
  `<relativePath/>   <!-- lookup parent from repository -->`  
  `</parent>`
* To find the repository details ( like npm )- https://central.sonatype.com/
* mvnw - maven wrapper files- help to run the maven project