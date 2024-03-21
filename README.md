# dokuwiki-plugin-datatemplate
Extension to the data plugin allowing for the use of templates.

For more information, visit the official plugin page at https://www.dokuwiki.org/plugin:datatemplate.

## Development status

Changelog is maintained on the [official plugin page](https://www.dokuwiki.org/plugin:datatemplate).
Here's just the changelog for the hci.ur.de fork

2024-03-22 - fix compatiblity issues caused mainly by a [commit renaming function in the data plugin](https://github.com/splitbrain/dokuwiki-plugin-data/commit/820f7b69ab991d98fcb477d9c2cf41aaecde87ec). 

2018-05-16 - (only in hci.ur.de fork)  Added a custom class that can be added to the datatemplatelist line: "nodiv". This prevents generation of ``<div>``tags around each data item when generating the list. Necessary for plugins that do not want individual items to be placed into divs (e.g. the [Bootstrap Wrapper plugin](http://www.lotar.altervista.org/wiki/wiki/plugin/bootswrapper)'s [carousel](http://www.lotar.altervista.org/wiki/wiki/plugin/bootswrapper/carousel)

2016-07 - The original author, [Christoph Clausen](https://github.com/ccl/dokuwiki-plugin-datatemplate), cannot maintain anymore the plugin, so I adopt it ;-) Thanks a lot to him to have built first steps and accepted the adoption.
