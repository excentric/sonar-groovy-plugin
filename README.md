
A fork of the Sonar Groovy Plugin v0.5 with the following changes:

 + now being built using gradle
 + adds 'Plugin-ChildFirstClassLoader: true' to the Manifest - solves an issue seen when trying to analyse groovy code from gradle
 + added clover support
 - removed cobertura support

To build the plugin:

    gradle jar

After you build the plugin - you can find original plugin documentation and installation instructions from http://docs.codehaus.org/display/SONAR/Groovy+Plugin

