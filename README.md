# IEX-Postman-Collections
This is a repository to hold the interface implementation of the [IEX cloud api](https://iexcloud.io/docs/api) in postman. More info on postman can be found [on their home page](https://www.getpostman.com/). This repository is ment to aid in developing tools that use IEX api by giving direct access to the endpoints in a way that a developer could experiment with.

## DEEP and TOPS
The "DEEP" and "TOPS" endpoints have been included for completeness under the "Investors Exchange Data.postman_collection.json" collection. These endpoints will work with postman however their true value lies in the web socket subscription to those data sources. It is not recommended to use a standard http request to those endpoints in an application.
