# Roboconf Maven Archetype
[![License](https://img.shields.io/hexpm/l/plug.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Join us on Gitter.im](https://img.shields.io/badge/gitter-join%20chat-brightgreen.svg)](https://gitter.im/roboconf/roboconf)
[![Web site](https://img.shields.io/badge/website-roboconf.github.io-b23e4b.svg)](https://roboconf.github.io)

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

