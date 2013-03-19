Kevin Deldycke's blog
=====================

These are the source files of the content and theme of my [blog](http://kevin.deldycke.com),
which is powered by [Pelican](http://getpelican.com), a static site generator written in Python.


TODO
----

  * Re-use previous artworks from Maomium ?
  * Test different ad placements: http://news.ycombinator.com/item?id=4974511
  * Hack google search to integrate search result within theme design ?
  * Replace Google custom search by https://swiftype.com/ ? Or better, static search: http://ralsina.com.ar/weblog/posts/standalone-search-in-nikola.html
  * Fix embedded video aspect-ratio
  * Use a big carousel for front-page articles (ex: http://twitter.github.com/bootstrap/examples/carousel.html ) + a bit of http://srobbin.com/jquery-plugins/backstretch/ to keep aspect-ratio
  * Check some web-dev essentials: http://webdevchecklist.com/
  * Add a fancy zoom for images
  * Get rid of /year/month/ in URL slug ? Or get rid of month only ?
  * Deduplicate articles' tags.
  * Use custom jinja filters instead of heavy tag soup in my theme ? Example: https://bitbucket.org/sirex/blog/src/32c192ff7a10/pelican.conf.py#cl-53
  * Simplify Amazon affiliates links ? See: http://www.linktrackr.com/blog/amazon-affiliate-link/
  * Automate Amazon link creation: https://github.com/rdegges/python-amazonify
  * Automate blog building and publishing on commit update with Fabric ? See: http://stackful-dev.com/easier-pelican-blogging-with-fabric-automation.html and https://pypi.python.org/pypi/pelicangit
  * Add progressive image loading. See: http://www.appelsiini.net/projects/lazyload
  * Concatenate and minify CSS and Javascript. For CSS, use: https://pypi.python.org/pypi/mincss . Also, have a look at: https://pypi.python.org/pypi/pelican-minify
  * Inline and embed all CSS in the page ? See: http://www.peterbe.com/plog/100-percent-inline-css
  * Use LESS version of bootstrap for cleaner customizations ?
  * Check and fix style on mobile (especially ugly margins)


License
-------

The content of this repository is copyrighted (c) 2004-2013 Kevin Deldycke.

Unless contrary mention, the licensing terms below applies:

  * Code and software released under [GNU/GPL licence, v2.0](http://www.fsf.org/licensing/licenses/gpl.html).
  * Other content published under [Creative Commons Attribution-Share Alike 3.0 license](http://creativecommons.org/licenses/by-sa/3.0/).


Third-party assets
------------------

The theme uses external softwares, scripts, libraries and artworks:

    Solarized Pygment style v0.1.0
    Copyright (c) 2012 Shoji KUMAGAI
    Distributed under a MIT license
    Source: http://pypi.python.org/pypi/pygments-style-solarized

    Fabric (Plaid)
    Copyright (c) 2012 James Basoo
    Distributed under a Creative Commons Attribution-ShareAlike 3.0 Unported license
    Source: http://subtlepatterns.com/fabric-plaid/

    Cream paper
    Copyright (c) 2012 Devin Holmes
    Distributed under a Creative Commons Attribution-ShareAlike 3.0 Unported license
    Source: http://subtlepatterns.com/cream-paper/
