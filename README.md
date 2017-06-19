imagej-command-archetype
========================

Maven archetype based on [https://github.com/imagej/example-imagej-command](https://github.com/imagej/example-imagej-command).

Usage
-----

1. `mvn install` this repository

2. Subsequently, you can start the interactive creation mode that let's you select a GAV for a new `Command` that will be created in a new subdirectory of the current directory with the name of your `Command`'s `artifactId`:

```
mvn archetype:generate \
    -DarchetypeGroupId=net.imagej \
    -DarchetypeArtifactId=imagej-command-archetype \
    -DarchetypeVersion=0.0.1-SNAPSHOT
```
