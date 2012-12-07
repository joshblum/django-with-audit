django-with-audit
=================

Whats different?
----------------------------

This modified version of Django 1.4.2 has signals for get queries to the database.

Specifically the signals `pre_get` and `post_get` have been added, modeled after the `pre_save` and `post_save` signals already available. 

Used in conjunction with [django-audit-log](https://github.com/joshblum/django-audit-log) and the example application [django-audit](https://github.com/joshblum/django-audit)