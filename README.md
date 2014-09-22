Drupal Ignite standard template
===============================

This project contains a Drupal 7 template project that can be used to quickly set up a new environment.
This template is intended to be used in conjuction with [Drupal ignite CLI](https://github.com/twinbit/drupal-ignite).

NOTICE
------

This software is in early development stage and could still change a lot, so don't get mad if it still has a few raw edges :)


Contents
--------

### root folder

* a tailored .gitignore file;
* a simple apache vhost conf file;
* a drush make file containing some basic modules and libraries;
* a behat.yml.dist file, containing a Drupal-optimized set of Behat configuration;
* some phing.properties files, containing the variables belonging to each environment;
* a phing build.xml file, containing some targets to build the site in the local, dev and stage environments;
* a composer.json file, containing all the dependencies needed by behat and phing;
* a phpunit.xml.dist, containing the default config for running phpunit tests.

### bin/ folder

* a small bash build file that downloads composer and phings and runs the build.

### dumps/ folder

* placeholder to make sure the directories is here. it will hold drush backups.

### features/ folder

* a bootstrap/Drupal/Ignite/ folder containing two Behat Contexts carrying some goodies;
* a files/ folder containing two images to use as fixtures.
* an example scenario.

### profiles/ folder

* it contains a very basic Drupal install profile.

### reports/ folder

* placeholder to make sure the directories is here. it will hold test results and code analysis reports.

### a _sites_ folder

* a drush folder containing alias configuration;
* a modules folder containing basic subfolders layout for future modules and features;
* an empty themes folder.

### a _test_ folder

* a phpunit bootstrap file;
* a csv file iterator;
* a migrate helper to load csv data sources.
