one-button-wp
=============

Pulls down the latest version of Wordpress and a starter theme. Wordpress runs in its own directory for easy updating via Git.

#Installation

* Create a directory named 'upload-data' above the web root
* Clone the repo into your web root `git clone --recursive git@github.com:jshakes/one-button-wp.git`
* Enter your database connection details for each environment your site will be viewed in (local, staging etc.) into wp-config.php
* Run `wp/wp-admin/install.php` to set up the site and install a database

#Submodules

This repo includes the official Wordpress Github repo and my Vanilla theme as submodules.