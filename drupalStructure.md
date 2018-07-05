[<< BACK](README.md)

### DIRECTORY STRUCTURE DRUPAL 8

I expose an example directory structure of a drupal project to better understand the commands that I explain in the rest of the sections.

Official documentation of drupal [Structure] (https://www.drupal.org/docs/8/understanding-drupal/directory-structure)


#### Typical structure

* base directory
	- /core
		.
		.
	- /libraries
		.
		.
	- /modules
		- /test1Module
			-/config
				-/install
				resource.test1Module.yml
				...			
			-/src
			-/templates
				test1Module.html.twig
			-/tests
				-/src
					-/unit
					...
				...
			...
		composer.json
		test1Module.info.yml
		test1Module.module		
		...
	- /profile
		...
	- /themes
		...
	- /sites
		...
	- /vendor	
	- index.php
	- composer.json
	- .htaccess
	- web.config
	- ..



[<< BACK](README.md)
