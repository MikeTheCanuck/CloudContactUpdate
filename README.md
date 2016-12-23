# Cloud Contact Update
Updating cloud contact data from external sources.

Initial work aims to pull external data from LinkedIn Contacts API and merge it with existing contacts in iCloud.

This is the form of API call that I've observed LinkedIn makes when you load the Connections page (https://www.linkedin.com/connected/#):
https://www.linkedin.com/connected/api/v2/contacts?start=40&count=10&fields=id%2Cname%2CfirstName%2ClastName%2Ccompany%2Ctitle%2Clocation%2Ctags%2Cemails%2Csources%2CdisplaySources%2CconnectionDate%2CsecureProfileImageUrl&sort=CREATED_DESC&_=1481999304007

## Requirements
This code was written using Python 3.5.2, using modules and packages current as of 2016-12-20.