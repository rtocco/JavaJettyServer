This directory structure was generated by following the maven tutorial
on their website.
https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

The classes for the project are located in 'src/main/java/com/databaseserver'.
The 'main' function is in databaseserver/app/Main.java.

Running 'mvn package' in the same directory as the pom.xml file will automatically
resolve any dependencies, build the project, and place a .jar file in the /target
directory.

After this, the server can be run by calling 'mvn exec:java' which was from a
stack overflow post found here:
http://stackoverflow.com/questions/1089285/maven-run-project
Again, this must be called in the same directory as the pom.xml file.
