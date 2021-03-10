Django Voting Changelog
=======================

1.0 (unreleased)
----------------

* Drop the ``voting.VERSION`` field, for now.
  Client code can use APIs such as ``pkg_resources.get_distribution()``
  to query or depend on specific versions of django-voting.

* Added Django migrations.

* Drop South migrations.


0.2 (2012-07-26)
----------------

* Django 1.4 compatibility (timezone support)
* Added a ``time_stamp`` field to ``Vote`` model
* Added South migrations.
