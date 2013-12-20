django-persistent-models
========================

A drop-in replacement for `django.db.models.Model` that provides a persistent
version of the model class.  Each `save()` call will create a new instance of
the object instead of updating it in place.

License
-------

BSD, short and sweet
