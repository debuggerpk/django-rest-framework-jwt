# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

Changes for the upcoming release can be found in the `changelog.d` directory in
this repository.

Do **NOT** add changelog entries here! This changelog is managed by
[towncrier](https://github.com/hawkowl/towncrier) and is compiled at release
time.

.. towncrier release notes start

1.13.0 (2019-04-23)
=====================

Features
--------

- Added `on_delete` to `tests.models.UserProfile.user` required by Django 2.2,
  and added Django 2.x, Python 3.7 and djangorestframework 3.9 to the support matrix. ([#9](https://github.com/Styria-Digital/django-rest-framework-jwt/pull/9))


1.12.10 (2018-12-21)
====================

No significant changes.


1.12.9 (2018-12-21)
====================

Misc
----

- Fixed inconsistent View names. ([#7](https://github.com/Styria-Digital/django-rest-framework-jwt/pull/7))


1.12.8 (2018-12-21)
====================

Misc
----

- Updated docs. Drop support for Django < 1.8 and DRF < 3.7.x. ([#6](https://github.com/Styria-Digital/django-rest-framework-jwt/pull/6))


1.12.7 (2018-12-17)
====================

Misc
----

- Switch to Travis CI build stages ([#3](https://github.com/Styria-Digital/django-rest-framework-jwt/pull/3))


1.12.3 (2018-12-13)
====================

Misc
----

- Project restructuring according to SDS code style and conventions. ([#2](https://github.com/Styria-Digital/django-rest-framework-jwt/pull/2))
