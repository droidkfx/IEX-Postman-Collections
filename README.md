# IEX-Postman-Collections
This is a repository to hold the interface implementation of the [IEX cloud api](https://iexcloud.io/docs/api) in postman. More info on postman can be found [on their home page](https://www.getpostman.com/). This repository is ment to aid in developing tools that use IEX api by giving direct access to the endpoints in a way that a developer could experiment with.

## Getting started
To use this interface in postman:
1. make sure you have the latest version of postman that supports the 2.1 collection format. 
2. Either clone the repository or download one of the releases. 
3. Using the import button in the top left of the postman application import all the *.json files.
4. Set the "secret_key" and "public_key" values to your IEX tokens for test in TEST_V1 and for production in PROD_V1. _Note: do not set the initial value for security purposes._

## DEEP and TOPS
The "DEEP" and "TOPS" endpoints have been included for completeness under the "Investors Exchange Data.postman_collection.json" collection. These endpoints will work with postman however their true value lies in the web socket subscription to those data sources. It is not recommended to use a standard http request to those endpoints in an application.
