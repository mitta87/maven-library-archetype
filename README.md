Made by tutorial from https://www.marosmars.com/blog/maven-archetype-tutorial

To generate archetype skeleton from scratch use:

`mvn archetype:generate -B -DarchetypeArtifactId=maven-archetype-archetype \
-DgroupId=com.dpoletaev.tutorial.archetype -DartifactId=maven-library-archetype \
-Dversion=1.0-SNAPSHOT
`

1. mvn clean istall
2. In the folder to generate project from this archetype execute command:

`mvn archetype:generate -DarchetypeArtifactId=maven-library-archetype -DarchetypeGroupId=com.marosmars.tutorial.archetype \
-DarchetypeVersion=1.0-SNAPSHOT -DgroupId=com.dpoletaev -DartifactId=generated-from-archetype -Dversion=1.0-SNAPSHOT \
-Dpackage=com.dpoletaev.generated -Dlibrary-name=TestLibrary -DinteractiveMode=false`