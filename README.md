phantomjs-cartridge
===================

PhantomJS Cartridge for OpenShift Cloud Hosting

This is a very simple cartridge for allowing an OpenShift application to utilize PhantomJS.  

Add the cartridge to your application with one of the following commands:
 - rhc cartridge add https://raw.github.com/tresbailey/phantomjs-cartridge/master/metadata/manifest.yml -a {app_name} 
 - rhc app create {name} https://raw.github.com/tresbailey/phantomjs-cartridge/master/metadata/manifest.yml

Then you can run phantomjs with the command:

  - $OPENSHIFT_PHANTOMJS_DIR/usr/phantomjs


