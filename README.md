Zappa Cashcat
========================

Prerequisites
========

Get a gliphy api key from the gliphy developers website.

Get a webhook url for your slack channel



Install Zappa
==================================================

Create a python3 virtual environment

``` {.sourceCode .console}
$ pip install virtualenv
$ which python3
$ /usr/local/bin/python3
$ virtualenv -p /usr/local/bin/python3 my_virtual_env
```

Activate the virtual environment


``` {.sourceCode .console}
$ source my_virtual_env/bin/activate
```

Clone github repository


``` {.sourceCode .console}
$ git clone 
```

Installation
============

Install required python modules.

``` {.sourceCode .console}
$ pip install -r requiremnts.txt
```

Update the S3 bucket net, giphy api key and slack url in the
zappa_settings.json file.

Deploy and test.


``` {.sourceCode .console}
$ zappa deploy dev
```

