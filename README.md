# fwtheme-django-ceda-div

Django app providing Django framework theme for Django-based web apps, themed for CEDA Division. Requires lower-level fwtheme-django.

## Installation

`fwtheme-django-ceda-div` can be installed directly from Github using pip:

```
$ pip install git+https://github.com/cedadev/fwtheme-django-ceda-div.git
```

In `settings.py`, this app should have an entry in INSTALLED_APPS *before* fwtheme_django for correct precedence, as its templates should override those of `fwtheme-django`. orgtheme-ceda-serv and orgtheme are referenced directly in-place on the ceda artefacts server for production (but can be istalled and included in INSTALLED_APPS for development purposes only).

```
    'fwtheme_django_ceda_div',
    'fwtheme_django',
```
