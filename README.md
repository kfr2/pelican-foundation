# Pelican-Foundation
Pelican-Foundation is a theme for [Pelican](http://blog.getpelican.com/) that makes heavy use of the [ZURB Foundation](http://foundation.zurb.com/) front-end framework.

## AUTHORS
* [Kevin Richardson](https://github.com/kfr2)

## LICENSE
Released under the MIT License.  See full details in the `LICENSE` file.

## DEMO
You can see the [theme in action](http://magically.us/) or the site code [here](https://github.com/kfr2/kfr2.github.com/blob/source).

![theme screenshot](https://raw.github.com/kfr2/pelican-foundation/master/screenshot.png)

## INSTALLATION
Download or clone the [repository](https://github.com/kfr2/pelican-foundation). Edit `pelicanconf.py` and modify the `THEME` variable to point to the downloaded theme location.

## PELICANCONF.PY
The following are the Pelican global variables currently supported by the theme.  You may wish to view [Kevin Richardson's pelicanconf.py](https://github.com/kfr2/kfr2.github.com/blob/source/pelicanconf.py) for more information.

### display settings
* `LOGO_URL` -- the URL of the logo for the site. If this is not set, the image will default to `static/img/default-logo.png`.
* `TAGLINE` -- the text to display underneath AUTHOR in the left-hand menu.
* `DISPLAY_PAGES_ON_MENU` = True/False.    If True, display a list of pages defined within `content/pages`
* `MENUITEMS` -- (('name1', 'url1'), ('name2', 'url2'))
* `LINKS` -- (('name1', 'url1'), ('name2', 'url2'))`
* FOOTER_MESSAGE -- the message to display in the footer of the page. Defaults to "Powered by Pelican and Pelican-Foundation."

### other
* `DEFAULT_DATE_FORMAT = ('%b %d, %Y')` -- date format for post publication dates
* `FEED_DOMAIN = SITEURL`.  The prefix URL for the Atom/RSS feeds.
* `FEED_ATOM` -- ATOM feed name.  ex: 'feeds/all.atom.xml'
* `FEED_RSS` -- RSS feed name.  ex: 'feeds/all.rss'
* `GOOGLE_ANALYTICS` -- the site's Google Analytics key string.

When developing locally, set the following variable:

`SITEURL = http://localhost:8000`

## Thanks to...
* Rodolfocontreras on Wikimedia Commons for releasing his beautiful [Art Noveau ornament image](http://commons.wikimedia.org/wiki/File:ART_NOVEAU.svg) under the CC BY-SA.
* [ZURB](http://zurb.com/) for creating Foundation.