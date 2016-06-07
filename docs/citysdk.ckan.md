# CitySDK CKAN Module





* * *

## Class: CkanModule
Instantiates an instance of the CitySDK CKAN object.

### CitySDK CKAN Module.CkanModule.enable(apiKey) 

Enable function. Stores the API key for this module and sets it as enabled.  It will also compare the CitySDK core's version number to the minimum number required as specified for this module.

**Parameters**

**apiKey**: `string`, The census API key.

**Returns**: `boolean`, True if enabled, false if not enabled.

### CitySDK CKAN Module.CkanModule.APIRequest(request, callback) 

Sends a SQL query to a CKAN server.

**Parameters**

**request**: `object`, JSON Object

**callback**: `function`, Sends a SQL query to a CKAN server.

**Returns**: `object`, JSON Object



* * *









