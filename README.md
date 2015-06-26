# camel-kafka-repo
Patched version of camel-kafka

Patching camel-kafka to fix a minor bug that causes NotifyBuilder to throw a null pointer exception. This is a stop-gap till the core project fixes this.


mvn install:install-file -DgroupId=org.apache.camel -DartifactId=camel-kafka -Dversion=2.15.1 -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true -Dfile=/Users/rahuljai/.m2/repository/org/apache/camel/camel-kafka/2.15.1/camel-kafka-2.15.1.jar
