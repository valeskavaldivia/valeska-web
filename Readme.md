
How to work on those sources files :
====================================

Install packages :
------------------

With rbenv, and with bundler package installed, use the commande :
	bundle install --path vendor/bundle

This will install the necessary packages to build the site.


Run locally the web site :
--------------------------

bundle exec middleman


Build the package to upload your web hosting platform :
-------------------------------------------------------

Run the command :
	bundle exec middleman build

This will create/update the build/ directory. You can then push its content to
your website.
