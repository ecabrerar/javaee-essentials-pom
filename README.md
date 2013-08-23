javaee-essentials-pom
=====================

Essentials Maven pom.xml to demonstrates how to use Maven in a multi-modules JEE Project.

As a general rule, it is better to find functional names for modules. However, it is usually easier to choose names
that represent a technology instead.

The following names were chosen:

* ejb - the module containing the EJBs.
* web - the module containing the Web application.
* appclient - the module containing the client side streamer application.
* wsappclient - the module containing the Web services client application.
* ear - the module producing the EAR which packages the EJBs and the Web application.

This is the easiest and most flexible structure to use.However, if you have many modules in the same directory you may consider finding commonalities between them and create subdirectories to partition them.

For more information visit:

http://java.dzone.com/articles/how-do-you-organise-maven-sub



