[<< BACK](README.md)

### DIRECTORY STRUCTURE DRUPAL 8

I expose an example directory structure of a drupal project to better understand the commands that I explain in the rest of the sections.

Official documentation of drupal [Structure] (https://www.drupal.org/docs/8/understanding-drupal/directory-structure)


#### Typical structure

![#c5f015](https://placehold.it/15/c5f015/000000?text=+)  Sample module for documentation

* **base directory**
	* **/core**
	    - ...
	* **/libraries**
	    - ...
	* **/modules**
	  - /Module1 ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	    - /config ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	      - /install ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	        - resource.Module1.yml ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	        - ...		
	    - /src ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	    - /templates ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	      - Module1.html.twig ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	    - /tests ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	      - /src ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	        - /Unit ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	          - Module1Test.php ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	          - ...           
	    - composer.json ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	    - Module1.info.yml ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 
	    - Module1.module ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 		
	    - ... 
	* **/profile**
	    - ...
	* **/themes**	
	    - ...
	* **/sites**
	    - ...
	* **/vendor**	
	    - ...
	* **index.php**
	* **composer.json**
	* **.htaccess**
	* **web.config**
	* ...



[<< BACK](README.md)
