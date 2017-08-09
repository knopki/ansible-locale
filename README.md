Deprecation warning
=======

Unmaintained project. Please, use good alternative: [tersmitten.locales](https://galaxy.ansible.com/tersmitten/locales/)

locale
========

Set locales in Debian-like systems.

Role Variables
--------------

 * *locale_lang* - $LANG
 * *locale_all* - $LC_ALL
 * *locale_numeric* - $LC_NUMERIC
 * *locale_time* - $LC_TIME
 * *locale_monetary* - $LC_MONETARY
 * *locale_paper* - $LC_PAPER
 * *locale_identification* - $LC_IDENTIFICATION
 * *locale_name* - $LC_NAME
 * *locale_address* - $LC_ADDRESS
 * *locale_telephone* - $LC_TELEPHONE
 * *locale_measurement* - $LC_MEASUREMENT
 * *locale_to_be_generated* - list of locales to be generated (take care to use value from /usr/share/i18n/SUPPORTED, as locale-gen exit with code 0 even with errors...)

License
-------

MIT

Author Information
------------------

Sergey Korolev (<korolev.srg@gmail.com>)
