
1.0.5 / 2013-02-08 
==================

  * Alias url_generator service to router to be compatible with application using UrlGeneratorServiceProvider
  * New documentation

1.0.4 / 2013-02-04 
==================

  * Add test for overriding exception controller
  * Update documentation
  * Allow to override the controller used for excetion handling

1.0.3 / 2013-02-03 
==================

  * %root_dir%/config and %root_dir% are now registered as locations for config locator
  * Ignore coverage directory
  * Normalize visibility in Controller
  * Ignore local phpunit.xml file
  * Restructure composer file
  * Add testcase for matcher and matcher_base_class
  * Add .gitattributes file to make downloads slimmer

1.0.2 / 2013-01-31 
==================

  * Fix typo in RoutingServiceProvider which previously would use an invalid class for matching.
  * Add matcher_base_class as a default option for `routing.options` to make the cached matcher extend from the correct class.

1.0.1 / 2013-01-31
==================

  * Add .gitattributes file to make downloads slimmer
  * Add CHANGELOG.md
