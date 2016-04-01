# rest_api
PHP object oriented design pattern to create a RESTful Webservice.

## Usage
Run test.php on a LAMP/WAMP-Stack. Edit the $requestMethod parameter in test.php to simulate different behaviour. 

## Expanding the Webservice
To extend or modify a Service navigate to "php_rest/views/". In this directory you put one folder for each resource you like to provide. Name a folder corresponding to that resource. Inside a sub-folder that represents a version you create the required Class. Give that Class and its file a name that is the same as the folder that you´ve created first inside "views" but followed by "View".
````
php_rest/
  ...
  views/
    Example/
      v1/
        ExampleView.php
    YourNewModule/
      v1/
        YourNewModuleView.php
````
## Author
Martin Wolf
