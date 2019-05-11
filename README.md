# Koodausta kiltiksellä - Demo

Seuraa näitä ohjeita asentaaksesi kaiken tarpeellisen.

## Tarkistetaan Python ja Pip

- `python --version`
- `pip --version`

Jos toinen näistä puuttuu, seuraa [näitä ohjeita](http://timmyreilly.azurewebsites.net/python-pip-virtualenv-installation-on-windows/)

## virtualenv

Asennetaan `virtualenv` ja `virtualenvwrapper`.

- `pip install virtualenv`
- `pip install virtualenvwrapper` tai `pip install virtualenvwrapper-win`

Luodaan uusi virtuaaliympäristö

- `mkvirtualenv demo`

Linkkejä:
- [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html)
- [virtualenvwrapper-win](https://pypi.org/project/virtualenvwrapper-win/)

## Asennetaan paketit

Kloonaa tämä repo, ja aja komento

- `pip install -r requirements.txt`

## Avataan demo

Siirry kansioon `demo` ja aloita demo komennolla `jupyter notebook`.
