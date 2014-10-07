blogComponents
========

This a content package project generated using the multimodule-content-package-archetype.

Building
--------

This project uses Maven for building. Common commands:

From the root directory, run "mvn clean install -P autoInstallPackage" to build the bundle and content package and install to a CQ instance.

From the bundle directory, run "mvn clean install -P autoInstallBundle" to build *just* the bundle and install to a CQ instance.

if you get an error while building this project for maven-bundle-plugin then please change it's version to any older version as I was working on AEM6, initially I also got this error so I have to update this plugin version in parent pom.xml file then it works for me.


Happy Coding 
Ankur Chauhan
