# 002_pcf_node_demo

#### To Build and run the application in local
`npm install && npm start`

#### To deploy the application to pcf 
`cf push`

* make sure to update the `manifest.yml` file with unique name for the host field.

### Note
The minimum memory allocation for a java spring application is 256mb. Make sure this memory is allocated for the application. 
Or use the switch `-m 256M` in the command line in `cf push`.

