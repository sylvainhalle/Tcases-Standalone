The [Tcases model generator](https://code.google.com/p/tcases/) is
distributed as an archive containing a directory of JAR files and a
batch file to invoke it properly.

This project contains an Ant script to create a single, stand-alone runnable
JAR that you can move over freely.

## Instructions

1. Clone the present projet into a folder.
2. Download the [latest distribution of
   Tcases](https://code.google.com/p/tcases/wiki/HowToDownload) (not
   included with this project).
3. Unzip the archive *into* the project. This should add folders `lib`,
   `bin` to the project.
4. Run Ant by typing `ant` from the project's top folder. This should
   produce a JAR named `tcases.jar` in that folder.
5. That JAR is stand-alone and runnable. Simply call `java -jar tcases.jar`
   from anywhere, and pass as command-line arguments the same you would
   with the original Tcases (read its documentation).

## Caveat emptor

This has been tested with version 1.3.0 of Tcases under Ubuntu. Your mileage
may vary.
