## Ramhill - derivative of Greymill.  
  
Graymill is a minimal, responsive theme for the [Pelican](http://blog.getpelican.com/) static site generator. It is based on the [Graymill](https://github.com/errnair/graymill).  

### Demo

### pelicanconf.py

#### Social Icons:
```python
SOCIAL = (('linkedin', 'https://www.linkedin.com/in/username'),
          ('github', 'https://github.com/username'),
          ('twitter', 'https://twitter.com/username'),
          ('facebook', 'https://facebook.com/userid'),
          )
```

#### Pagination:
```python
DEFAULT_PAGINATION = 8
```

#### Home page parameters:

```python
SITEDESCRIPTION = 'your-site's-tagline'
DISPLAY_SUMMARY = True
DISPLAY_PAGES_ON_MENU = True
```

#### Other Settings
```python
FAVICON = 'images/favicon.png'
STATIC_PATHS = ['images', 'extras']
EXTRA_PATH_METADATA = {
    'extras/.htaccess': {'path': '.htaccess'},
    'extras/robots.txt': {'path': 'robots.txt'},
```

#### For local development:
```
SITEURL = 'http://localhost:8000'
```

### publishconf.py

When you are ready to publish your site add the following settings to `publishconf.py` file

```python
SITEURL = 'https://domain-name.tld'

FEED_ALL_ATOM = 'feeds/all.atom.xml'
CATEGORY_FEED_ATOM = 'feeds/%s.atom.xml'

GOOGLE_ANALYTICS = ""
```

For more information on publishing your site, please read the [Pelican publishing docs](http://docs.getpelican.com/en/3.6.3/publish.html)
