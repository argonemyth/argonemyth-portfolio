argonemyth-portfolio
====================

What's this?
------------
A django app that manage your dev projects and display them as portfolio.

Installation
------------
1. `pip install -e https://github.com/argonemyth/argonemyth-portfolio.git#egg=argonemyth-portfolio`
2. Add `portfolio` to `INSTALLED_APPS`.
3. Include URL's into your project's `urls.py`, like such::

        urlpatterns = patterns('',
            (r'^portfolio/', include('portfolio.urls')),
            ...
        )
