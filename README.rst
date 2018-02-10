===================================
Web Scrape Instagram Stories in Go_
===================================

.. image:: https://img.shields.io/badge/Language-Go-blue.svg
   :target: https://golang.org/

.. image:: https://godoc.org/github.com/siongui/goigfollow?status.png
   :target: https://godoc.org/github.com/siongui/goigfollow

.. image:: https://api.travis-ci.org/siongui/goigfollow.png?branch=master
   :target: https://travis-ci.org/siongui/goigfollow

.. image:: https://goreportcard.com/badge/github.com/siongui/goigfollow
   :target: https://goreportcard.com/report/github.com/siongui/goigfollow

.. image:: https://img.shields.io/badge/license-Unlicense-blue.svg
   :target: https://raw.githubusercontent.com/siongui/goigfollow/master/UNLICENSE

.. image:: https://img.shields.io/badge/Status-Beta-brightgreen.svg

.. image:: https://img.shields.io/twitter/url/https/github.com/siongui/goigfollow.svg?style=social
   :target: https://twitter.com/intent/tweet?text=Wow:&url=%5Bobject%20Object%5D


Get Instagram_ following and followers in Go_.


Obtain Cookies
++++++++++++++

The following three values are must to access the Instagram story API.

- ``ds_user_id``
- ``sessionid``
- ``csrftoken``

First login to Instagram_ from Chrome browser, and there are two ways to get the
above information:

1. From `Chrome Developer Tools`_: See this `SO answer`_ or `Obtain cookies`_
   section in `instastories-backup`_ repo.

.. image:: https://i.stack.imgur.com/psJLZ.png
   :align: center
   :alt: ds_user_id sessionid csrftoken

2. From Chrome extension: Use EditThisCookie_ or `cookie-txt-export`_ or other
   cookie tools.


UNLICENSE
+++++++++

Released in public domain. See UNLICENSE_.


References
++++++++++

.. [1] | `Unofficial Instagram API - Google search <https://www.google.com/search?q=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - DuckDuckGo search <https://duckduckgo.com/?q=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Ecosia search <https://www.ecosia.org/search?q=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Qwant search <https://www.qwant.com/?q=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Bing search <https://www.bing.com/search?q=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Yahoo search <https://search.yahoo.com/search?p=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Baidu search <https://www.baidu.com/s?wd=Unofficial+Instagram+API>`_
       | `Unofficial Instagram API - Yandex search <https://www.yandex.com/search/?text=Unofficial+Instagram+API>`_
.. [2] `GitHub - LevPasha/Instagram-API-python: Unofficial instagram API, give you access to ALL instagram features (like, follow, upload photo and video and etc)! Write on python. <https://github.com/LevPasha/Instagram-API-python>`_
.. [3] `GitHub - mgp25/Instagram-API: Instagram's private API <https://github.com/mgp25/Instagram-API>`_
.. [4] `GitHub - rarcega/instagram-scraper: Scrapes an instagram user's photos and videos <https://github.com/rarcega/instagram-scraper>`_
.. [5] `GitHub - cernyjan/Instagram-downloader: Downloader for Instagram photos in full resolution <https://github.com/cernyjan/Instagram-downloader>`_


.. _Go: https://golang.org/
.. _UNLICENSE: http://unlicense.org/
.. _Web Scrape: https://www.google.com/search?q=Web+Scrape
.. _EditThisCookie: https://www.google.com/search?q=EditThisCookie
.. _cookie-txt-export: https://github.com/siongui/cookie-txt-export.go
.. _Obtain cookies: https://github.com/hoschiCZ/instastories-backup#obtain-cookies
.. _instastories-backup: https://github.com/hoschiCZ/instastories-backup
.. _Chrome Developer Tools: https://developer.chrome.com/devtools
.. _SO answer: https://stackoverflow.com/a/44773079
.. _Instagram: https://www.instagram.com/
.. _goinsta: https://github.com/ahmdrz/goinsta
.. _types.go: https://github.com/ahmdrz/goinsta/blob/master/response/types.go
