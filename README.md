# rest_api
Objectoriented Pattern to create a RESTful Webservice.

## Usage
Run test.php on a LAMP/WAMP-Stack. Edit the $requestMethod parameter in test.php to simulate different behaviour. 

## Expanding the Webservice
To extend or modify a Service navigate to "php_rest/views/". In this directory you place one folder for each available resource you like to provide. Name a folder corresponding to the resource. Inside a sub-folder that represents a version you create the Class. Give the Class and its file a name which must be the same as the folder that you´ve created first inside "views" followed by "View".
````
php_rest/
  ...
  views/
    YourModule/
      v1/
        YourModuleView.php
````
