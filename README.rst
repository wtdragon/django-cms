##########
CI Deployment Based Django-CMS
##########

********
Features
********

* hierarchical pages
* extensive built-in support for multilingual websites
* multi-site support
* draft/publish workflows
* version control
* a sophisticated publishing architecture, that's also usable in your own applications
* frontend content editing
* a hierarchical content structure for nested plugins
* an extensible navigation system that your own applications can hook into
* SEO-friendly URLs
* designed to integrate thoroughly into other applications

Developing applications that integrate with and take advantage of django CMS features is easy and well-documented.

More information on `our website <https://www.django-cms.org>`_.

************
Requirements
************

See the `Python/Django requirements for the current release version
<http://docs.django-cms.org/en/latest/#software-version-requirements-and-release-notes>`_ in our documentation.

See the `installation how-to guide for an overview of some other requirements and dependencies of the current release
<http://docs.django-cms.org/en/latest/how_to/install.html>`_

*************
Documentation
*************

We maintain documentation for several versions of the project. Key versions are:

* `stable <http://docs.django-cms.org>`_ (default), for the **current release** version
* `latest <http://docs.django-cms.org/en/latest/>`_, representing the latest build of the **release-3.4.x branch**
* `develop <http://docs.django-cms.org/en/develop/>`_, representing the latest build of the **develop branch**

For more information about our branch policy, see `Branches
<http://docs.django-cms.org/en/latest/contributing/development-policies.html>`_.

Our documentation is hosted courtesy of `Read the Docs <https://readthedocs.org>`_.

***********
Quick Start
***********

You can use the `django CMS installer <https://djangocms-installer.readthedocs.io>`_::

    $ pip install --upgrade virtualenv
    $ virtualenv env
    $ source env/bin/activate
    (env) $ pip install djangocms-installer
    (env) $ mkdir myproject && cd myproject
    (env) $ djangocms -f -p . my_demo
    (env) $ python manage.py


************
Getting Help
************



******************
Commercial support
******************

This project is backed by `Divio <https://www.divio.com/en/commercial-support/>`_.
If you need help implementing or hosting django CMS, please contact us:
sales@divio.com.

*******
Credits
*******

* Includes icons from `FamFamFam <http://www.famfamfam.com>`_.
* Python tree engine powered by
  `django-treebeard <https://tabo.pe/projects/django-treebeard/>`_.
* JavaScript tree in admin uses `jsTree <https://www.jstree.com>`_.
* Many thanks to
  `all the contributors <https://github.com/divio/django-cms/graphs/contributors>`_
  to django CMS!
