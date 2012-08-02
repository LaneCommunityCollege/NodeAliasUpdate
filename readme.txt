Node Alias Update

This module was developed as part of Lane Community College's (http://www.lanecc.edu) migration to Drupal.

When assigning URLs via taxonomy, it's convenient to be able to update the urls of all the nodes under those terms when one of the term names changes. This module hooks into taxonomy_term_update to build a list of nodes and child term nodes that will get new URLs, updates the URLs, then clears your Drupal and (if installed) Varnish caches. 

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/
