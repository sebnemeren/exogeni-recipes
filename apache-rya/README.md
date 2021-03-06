This recipe installs and configures Apache Rya on top of the [accumulo](../accumulo/) recipe.  Please see that README for details on the Accumulo installation. Starting with a base OS image represents a trade-off between customizability and fast startup times -- after ExoGENI reports the nodes are available, installation and configuration of Apache Rya will take approximately 30 minutes.

## Web Interfaces
_WARNING_ these web interfaces are currently open with unrestricted/unauthenticated world-wide public internet access. Also please note the warning on web interfaces from the [hadoop 2.7.3](../hadoop/hadoop-2.7.3/) and [accumulo](../accumulo/) recipes.
* Rya web: http://AccumuloMaster:8080/web.rya/sparqlQuery.jsp
* Rya OpenRDF Workbench: http://AccumuloMaster:8080/openrdf-workbench/

## References
* https://rya.apache.org/
* https://github.com/apache/incubator-rya
