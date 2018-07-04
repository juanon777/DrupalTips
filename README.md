# DrupalTips
Tips for DRUPAL (drush commands, modules...)

## BASICS DRUSH COMMANDS

#### DATABASE COMMANDS

Sometimes you work on a drupal project with multiple git branches. It's possible that certain modules don't exist in certain branches and can leave your drupal inconsistent if you go from one branch to another without updating the database. Having a backup of your databases is a good idea. 

We assume that the sql files are in the drupal base directory. If not, put the full path of the file.


#### Drop drupal database

From your base project directory, launch:

```
drush sql-drop
```

Will ask you confirmation to launch the command.

#### Export drupal database

From your base project directory, launch:

```
drush cr
drush sql-dump > my-sql-dump-file-name.sql
```
Clear cache is recommended.

#### Import drupal database

From your base project directory, launch:

```
drush sql-drop
drush sql-cli < my-sql-dump-file-name.sql
```

Will ask you confirmation to the **sql-drop** command. 
