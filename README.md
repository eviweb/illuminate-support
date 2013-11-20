Illuminate Redefined Support Classes
====================================
This package provides some redefinition of default implementations of the
Illuminate/Support package
[![Build Status](https://travis-ci.org/eviweb/illuminate-support.png?branch=master)]
(https://travis-ci.org/eviweb/illuminate-support)
How to install
==============
Just run `composer require eviweb/illuminate-support:dev-master`
How to use
==========
Simply depend on classes of this package instead of the original ones.
eq. To rely on the redefined ServiceProvider, copy and paste the following line to
your class definition file `use evidev\illuminate\redefined\support\ServiceProvider;`
and make your class inherit from this one.
