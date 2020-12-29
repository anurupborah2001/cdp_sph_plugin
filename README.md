#CDP Activation Service
CDP Activation Service is a service in SPH Wave that shows the banner in the clients webpage based on multiple parameters passes to the activation service. 

The following are the process to make the ECS deployment to AWS from local : 

#### Dependencies
1. HBase
2. MYSQL RDBMS

#### Requirements to run in localhost
1. Need to install HBase locally and insert the data to HBase.
2. Need to install MySQL and need to run the migration script under resource/db.migration in the project folder 
to import dummy data.
3. To run the project need to run the HBase and MySQL and than run the project

### CDP Activation service UI Javascript
 The javascript plugin to call the Activation service API is under "ui" foler
 ui/cdp.js
 
# Reference of API

Request API

Production URL : https://cdp.activation.sph.com.sg/api/activation

Development URL : https://dev-cdp.activation.sph.com.sg/api/activation

Swagger Development URL : https://dev-cdp.activation.sph.com.sg/swagger-ui/

Method : POST

Headers : x-api-key : <api-key-value>

