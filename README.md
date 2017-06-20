imagej-command-archetype
========================

Maven archetype based on [https://github.com/imagej/example-imagej-command](https://github.com/imagej/example-imagej-command).

Usage
-----

1. `mvn install` this repository

2. Subsequently, you can start the interactive creation mode that let's you select a GAV for a new `Command` that will be created in a new subdirectory of the current directory with the name of your `Command`'s `artifactId`:

```
$ mvn archetype:generate \
    -DarchetypeGroupId=net.imagej \
    -DarchetypeArtifactId=imagej-command-archetype \
    -DarchetypeVersion=0.0.1-SNAPSHOT
```

**Interactive mode for GAV definition:**
```
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Stub Project (No POM) 1
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] >>> maven-archetype-plugin:2.2:generate (default-cli) > generate-sources @ standalone-pom >>>
[INFO]
[INFO] <<< maven-archetype-plugin:2.2:generate (default-cli) < generate-sources @ standalone-pom <<<
[INFO]
[INFO]
[INFO] --- maven-archetype-plugin:2.2:generate (default-cli) @ standalone-pom ---
[INFO] Generating project in Interactive mode
[INFO] Archetype repository missing. Using the one from [net.imagej:imagej-command-archetype:0.0.1-SNAPSHOT] found in catalog local
Define value for property 'groupId': : com.mycompany
Define value for property 'artifactId': : GaussFiltering
Define value for property 'version':  1.0-SNAPSHOT: : 0.1.0-SNAPSHOT
Define value for property 'package':  com.mycompany: :
Confirm properties configuration:
groupId: com.mycompany
artifactId: GaussFiltering
version: 0.1.0-SNAPSHOT
package: com.mycompany
 Y: : Y
```
