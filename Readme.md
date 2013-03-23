Eclipse Online recipe for Calibre
=================================

[Eclipse Online](http://www.nightshadebooks.com/category/eclipse/) is a free short fiction publication edited by [Jonathan Strahan](http://www.jonathanstrahan.com.au) and published online by [Night Shade Books](http://www.nightshadebooks.com/). [Calibre](http://www.calibre-ebook.com/) is a free and open source ebook library management program, extensible with "recipes" for assembling ebooks from arbitrary sources. This repository contains a Calibre recipe to compile an ebook from recent installments of Eclipse Online. Now you can read "the rare and unusual, the strange and eldritch" on your Kindle or other e-reader.

Disclaimer
----------

This script is not endorsed by Eclipse Online. It is intended only as a personal convenience for fans of the publication. Please do not distribute unauthorized ebooks of Eclipse Online. Please do share links to <http://www.nightshadebooks.com/category/eclipse/>!

Installation
------------

To add this recipe to Calibre:

1. Select *Add a custom news source* from the *Fetch news* menu.
2. Click *Load recipe from file* and select `eclipseonline.recipe`, downloaded from this repository.

By default, the recipe will only download content posted in the last month. You can increase the value of the `oldest_article` variable to retrieve older posts. However, the Eclipse Online RSS feed currently only provides links to the 10 most recent posts, making that the maximum that can be retrieved by this recipe.

Usage
-----

To schedule ebook downloads:

1. Select *Schedule news download* from the *Fetch news* menu.
2. Select *Eclipse Online* from the *Custom* recipe category.
3. Check *Schedule for download*. I recommend selecting *Days of month* and entering *1* in the *Days of the month* field, as pictured below. Click *Save*. Together with the default 32-day download window mentioned above, this will result in "monthly issues" of Eclipse Online. (Alternatively, you can just click *Download now* to retrieve copies manually.)

