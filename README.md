one-button-wp
=============

Pulls down the Wordpress repo and a starter theme. Wordpress runs independently of your code for easy updating via Git.

#Installation

* Clone the repo into your sites directory using `git clone --recursive git@github.com:jshakes/one-button-wp.git` (It only needs to be read-only) and rename the directory when done.
* Change directory into wp and switch to the latest stable tagged release, eg. `git checkout 3.4.1`
* In `wp-config.php` Enter your database connection details for each environment your site will be viewed in (local, staging etc.) into the $connections array in
* Run `wp/wp-admin/install.php` to build the database tables.