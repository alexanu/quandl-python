### unreleased
* Remove dependency on unittest2, use unittest instead (#113)

### 3.4.5 - 2018-11-21

* Use POST requests for some datatable calls https://github.com/quandl/quandl-python/pull/126

### 3.4.4 - 2018-10-24

* Add functionality to automatically retry failed API calls https://github.com/quandl/quandl-python/pull/124

### 3.4.3 - 2018-10-19

* Allow for exporting of datatables https://github.com/quandl/quandl-python/pull/120

### 3.4.2 - 2018-08-21

* Fix typos in our warning messages https://github.com/quandl/quandl-python/pull/114

### 3.4.1 - 2018-07-25

* Include all documentation and test file in source distribution (sdist) tarballs

### 3.4.0 - 2018-07-03

* When returning a list of data, in a Python friendly format, convert datetime64 to datetime
* Numpy no longer supports Python v3.3, thus we are removing support for it

### 3.3.0 - 2017-12-20

* Unlock the version of requests to allow use with other modern packages

### 3.2.1 - 2017-10-23

* Provide a more actionable warning when asking for data over 1M rows

### 3.2.0 - 2017-06-14

* Add test support for python 3.6.

* Raise error when over 1000000 rows when fetching tables with paginate

* Pandas fix for newer pandas version.

* Bug fixes

### 3.1.0 - 2017-03-07

* Bug: support column with a name 'code'

### 3.0.1 - 2016-05-25

* Handle unexpected errors

### 3.0.0 - 2016-04-22

* Datatables for developers
* Datatables for analysts
* Backwards compatibility
* Documentation updates
