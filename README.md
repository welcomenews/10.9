### Install

$ apt install py-pip
$ python3 -m venv venv
$ source venv / bin / activate
$ pip install setuptools testinfra


```
/etc/nginx/test # pytest test.py 
/usr/lib/python2.7/site-packages/testinfra/__init__.py:32: TestinfraDeprecationWarning: DEPRECATION: testinfra python2 support is unmaintained, please upgrade to python3
  stacklevel=1)
========================================================================= test session starts ==========================================================================
platform linux2 -- Python 2.7.18, pytest-4.6.11, py-1.11.0, pluggy-0.13.1
rootdir: /etc/nginx/test
plugins: testinfra-3.4.0
collected 2 items                                                                                                                                                      

test.py ..                                                                                                                                                       [100%]

======================================================================= 2 passed in 0.27 seconds =======================================================================

```
