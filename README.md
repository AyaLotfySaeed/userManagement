# User Management System
## Instructions 
1. Add the war file in the webapps folder
2. I used a local tomcat server so the url is http://localhost:8080/v1/groups/{end_point}
3. To run the endpoints, use the swagger json file to find samples
 by uploading the file on https://editor.swagger.io/
## Assumptions 
1. User group has one or more sub user groups, but sub user groups can't have sub user groups
2. If there is an issue while executing any end point, the end point will respond by a body of null values
