
# pubhubWSClient
Using the JAX-WS Maven Plugin the projects pom file generates a client for the PubHub web service (https://service.pubhub.dk/).


Currently the following WSDL is used (see pom.xml):

http://service.qa.pubhub.dk/Retailer/V17/MediaService.asmx?WSDL


To use the pubhubWSClient in an other maven project run:

* mvn clean install


To inspect the generated code (can be found in target/generated-sources) run:

* mvn clean package
