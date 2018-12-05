[![PyPI version](https://badge.fury.io/py/django-inspectdb-refactor.svg)](https://badge.fury.io/py/django-inspectdb-refactor)

Django Inspectdb Refactor Fork
========================
This is a form of https://github.com/farhan0581/django-inspectdb-refactor to fix the compatibility issue with latest inspectdb

updated in management/commands/inspector_refactor.py:

```
- for meta_line in self.get_meta(table_name, constraints, column_to_field_name):


+  for meta_line in self.get_meta(table_name, constraints, column_to_field_name, False):
``` 

For full documentation see:
https://github.com/farhan0581/django-inspectdb-refactor 

