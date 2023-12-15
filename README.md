# Welcome Note
This Postman collection provides ways to configure FortiSASE portal via REST API, in automated fashion. 

# Versioning 
Curent version supports the following API possibilities, and therefore the postman collections: 
- Raw collection file can be downloaded here at [FSS Raw Collection](https://raw.githubusercontent.com/fortinet-solutions-cse/fss_postman_collection/main/fss_spa.postman_collection.json) 
- Supporting Environment file can be downloaded at  [Environment](https://github.com/fortinet-solutions-cse/fss_postman_collection/blob/main/fss_spa_environment.json)

# Setup Steps: 
- import [FSS Raw Collection](https://raw.githubusercontent.com/fortinet-solutions-cse/fss_postman_collection/main/fss.postman_collection.json) file into your Postman 
- import the supporting [Environment](https://github.com/fortinet-solutions-cse/fss_postman_collection/blob/main/fss_environment.json) file into Postman 
- make sure you add your FSS Bearer token in _-Authorization__ section of the parent folder, as shown in the picture below. How to obtain the token is explained at the following Fortinet [FNDN page](https://fndn.fortinet.net/index.php?/fortiapi/2625-fortisase/2640/).

![](images/pm_authorization.png){#fig:unisase_infra .center width=90%}

- make sure you populate the environment file with necessary variables (```including the bearer token too!```): 

![](images/pm_environment_vars.png){#fig:unisase_infra .center width=90%}







