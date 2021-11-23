mozilla-django-oidc-demo
====================================
* This repository is experimental for mozilla-django-oidc.
* PyPI https://pypi.org/project/mozilla-django-oidc/
* Github https://github.com/mozilla/mozilla-django-oidc
* Readthedocs https://mozilla-django-oidc.readthedocs.io
* Mozilla https://infosec.mozilla.org/guidelines/iam/openid_connect.html

Demo app installation
====================================
* Get repo and runserver.

.. code::

    $ git clone git@github.com:HumanBrainProject/mozilla-django-oidc-demo.git
    $ cd mozilla-django-oidc-demo
    $ python3 -m venv venv
    $ source venv/bin/activate
    $ pip install setuptools --upgrade && pip install pip --upgrade
    $ pip install -r requirements.txt
    $ cp .env.ebrains .env  # Please check env variables.
    $ python manage.py migrate
    $ python manage.py runserver 127.0.0.1:8000

* Access with your browser.

.. code::

    http://localhost:8000/

