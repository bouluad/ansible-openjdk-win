# ansible-openjdk-win

This role performs the following tasks:

Downloads the JDK 11 ZIP archive from the OpenJDK website.
Extracts the ZIP archive to C:\Java.
Sets the JAVA_HOME environment variable to C:\Java\jdk-11.0.9.
Adds %JAVA_HOME%\bin to the PATH environment variable.
