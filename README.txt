Drupal 8 module to output facet links as Boostrap components.

Depends on the Facets module:

https://www.drupal.org/project/facets

List group, single button dropdown, and split button dropdown are the currently available components.

Requires Bootstrap 3 through the Drupal Bootstrap theme or by any other means.

This also requires the following patch (or later since it looks like I need to fix the tests on that one) to the Facets module:

https://www.drupal.org/node/2855320#comment-12131700

How do I use this?

When editing/configuring a facet, use the "List of Links" widget. In the "Settings" fieldset select the Bootstrap component you'd like.