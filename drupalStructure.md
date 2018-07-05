[<< BACK](README.md)

### DIRECTORY STRUCTURE DRUPAL 8

I expose an example directory structure of a drupal project to better understand the commands that I explain in the rest of the sections.

Official documentation of drupal [Structure] (https://www.drupal.org/docs/8/understanding-drupal/directory-structure)


#### Typical structure

* base directory
	* /core
	  ...
	* /libraries
    	  ...
	* /modules
	  - /Module1
	    - /config
	      - /install
	        - resource.Module1.yml
	        - ...			
	    - /src
	    - /templates
	      - Module1.html.twig
	  - /tests
	    - /src
	      - /Unit
	        - Module1Test.php
	        - ...           
	    - composer.json
	    - Module1.info.yml
	    - Module1.module		
	    - ...
	* /profile
	  - ...
	* /themes
          - ...
	* /sites
	  - ...
	* /vendor	
	  - ...
	* index.php
	* composer.json
	* .htaccess
	* web.config
	* ...



[<< BACK](README.md)
