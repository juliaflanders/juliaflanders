# ReadMe

The original readMe file describing Jekyll Now and the quick start and update process can be found at <https://github.com/barryclark/jekyll-now/blob/master/README.md>. 

My own adaptations of this theme are so far mostly experimental in an effort to learn more about how Jekyll works. However, I've also experimentally added CETEICean (https://github.com/TEIC/CETEIcean) so that I can publish TEI-encoded data, and I've experimented with modifying that code so that I can publish XML that is not TEI. 

Notes for me on the various components of the site and what they do:
* config.yaml: contains the overall configuration settings for the site (avatar, footer, etc.)
* files in the layouts directory: these control what HTML is used in the pages generated for the site
* files in the pages directory: these represent specific "static" pages on the site (i.e. they are reached by specific navigational paths rather than accumulating in sequence like posts)
* files in the posts directory: these represent the individual blog postings
* files in the \_sass directory: these define consistent style elements for use across the site (e.g. colors, fonts); these are then referenced from the styles.scss file
* files in the xml directory are TEI and other XML files and their accompanying HTML wrappers, referenced by CETEICean
* files in the js directory are the code used by CETEICean in the display of TEI files.

