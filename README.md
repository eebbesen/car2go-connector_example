# car2go-connector_user
Example project showing usage of the Car2Go Mule Anypoint connector

## Installing
You will have to manually install this connector until it is publicly available.  See https://docs.mulesoft.com/anypoint-connector-devkit/v/3.7/installing-and-testing-your-connector-in-studio for instructions.

## Running
You will need a Car2Go API key -- it can be obtained by emailing openapi@car2go.com.

Until car2go-connector gets into the Maven Central repository you may have to install it manually:

     mvn deploy:deploy-file -DgroupId=com.humegatech -DartifactId=car2go-connector -Dversion=1.1.3-SNAPSHOT -Durl=file:./lib/ -DrepositoryId=local-maven-repo -DupdateReleaseInfo=true -Dfile=./lib/car2go-connector-1.1.3-SNAPSHOT.jar