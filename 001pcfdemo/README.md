# 001pcfdemo

#### To Build the application
`gradle build`

#### To deploy the application to pcf 
`cf push pcfdemo1 -p ./build/libs/demo1-0.0.1-SNAPSHOT.jar -b https://github.com/cloudfoundry/java-buildpack.git`

### Note
The minimum memory allocation for a java spring application is 256mb. Make sure this memory is allocated for the application. 
Or use the switch `-m 256M` in the command line in `cf push`.

