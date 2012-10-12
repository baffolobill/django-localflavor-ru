=====================
django_localflavor_ru
=====================

Country-specific Django helpers for Russia.

What's in the Russia localflavor?
=================================

* forms.RUPostalCodeField: Russian Postal code field. The valid format is
  XXXXXX, where X is any digit and the first digit is not zero.

* forms.RUCountySelect: A ``Select`` widget that uses a list of Russian
  Counties as its choices.

* forms.RURegionSelect: A ``Select`` widget that uses a list of Russian Regions
  as its choices.

* forms.RUPassportNumberField: Russian internal passport number. The valid
  format is XXXX XXXXXX, where X is any digit.

* forms.RUAlienPassportNumberField: Russian alien's passport number. The valid
  format is XX XXXXXXX, where X is any digit.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
