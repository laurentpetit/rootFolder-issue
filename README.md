rootFolder-issue
================

Small maven tycho project demonstrating that rootFolder property does not work properly

== Usage

Run 

  mvn clean verify
  
Then see that, despite the fact that `rootFolder` is set in file `product/pom.xml`, no produced zip file contains a root folder.  
