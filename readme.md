# Roboconf Maven Archetype
[![License](https://pypip.in/license/apache-libcloud/badge.png)](http://www.apache.org/licenses/LICENSE-2.0)

Website: [http://roboconf.net](http://roboconf.net)  
Licensed under the terms of the **Apache License v2**.

A Maven archetype for Roboconf projects.  
Use the following command to create a new Roboconf project from this archetype.

```
mvn archetype:generate                              \
  -DarchetypeGroupId=net.roboconf                   \
  -DarchetypeArtifactId=roboconf-maven-archetype    \
  -DarchetypeVersion=1.0                            \
  -DgroupId=<my.groupid>                            \
  -DartifactId=<my-artifactId>
```

Because there should not be a lot of versions of this archetype,
it was placed in its own Git repository. Like the **Roboconf parent**,
it should be released on demand, independently of the Roboconf roadmap. 
