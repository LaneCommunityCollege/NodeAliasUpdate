Node Alias Update

This module was developed as part of Lane Community College's (http://www.lanecc.edu) migration to Drupal.

When assigning URLs via taxonomy, it's convenient to be able to update the urls of all the nodes under those terms when one of the term names changes. This module hooks into taxonomy_term_update to build a list of nodes and child term nodes that will get new URLs, updates the URLs, then clears your Drupal and (if installed) Varnish caches. 
