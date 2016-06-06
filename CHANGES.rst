Changes
=======

.. contents::

0.1.3 (2016-06-06)
------------------

* Override ``AUTOLOGIN_USERNAME``, ``AUTOLOGIN_PASSWORD``,
  ``AUTOLOGIN_EXTRA_JS``, ``AUTOLOGIN_LOGIN_URL`` and
  ``AUTOLOGIN_LOGOUT_URL`` via lower-case keys in ``request.meta``.


0.1.2 (2016-05-25)
------------------

* ``AUTOLOGIN_CHECK_LOGOUT`` setting to disable logout detection.
* An issue with erasing callbacks for retried requests was fixed.


0.1.1 (2016-05-20)
------------------

* Do not use proxy when calling autologin http api.


0.1.0 (2016-05-20)
------------------

Initial release
