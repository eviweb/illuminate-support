Illuminate Redefined Support Classes
====================================

This package provides some redefinition of default implementations of the Illuminate/Support package

Build Status
------------

**Travis CI:** [![Build Status](https://travis-ci.org/eviweb/illuminate-support.png?branch=master)](https://travis-ci.org/eviweb/illuminate-support)

**Scrutinizer CI:** [![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/eviweb/illuminate-support/badges/quality-score.png?s=2026969fc96e03f49b3fdce896a3980aeb7b71b4)](https://scrutinizer-ci.com/g/eviweb/illuminate-support/)

How to install
--------------

Just run `composer require eviweb/illuminate-support:dev-master`

How to use
----------

Simply depend on classes of this package instead of the original ones.
eq. To rely on the redefined ServiceProvider, copy and paste the following line to
your class definition file `use evidev\illuminate\redefined\support\ServiceProvider;`
and make your class inherit from this one.
