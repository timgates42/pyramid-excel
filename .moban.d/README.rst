{%extends 'WEB-README.rst.jj2' %}

{%block header %}
Tested Pyramid Versions
========================

.. image:: https://img.shields.io/badge/pyramid-1.9-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

.. image:: https://img.shields.io/badge/pyramid-1.8.4-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

.. image:: https://img.shields.io/badge/pyramid-1.7.6-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

.. image:: https://img.shields.io/badge/pyramid-1.6.1-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

.. image:: https://img.shields.io/badge/pyramid-1.5.8-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

.. image:: https://img.shields.io/badge/pyramid-1.4.9-green.svg
    :target: http://travis-ci.org/pyexcel/pyramid-excel

{%endblock%}


{%block setup%}
Setup
======
Once the pyramid_excel is installed, you must use the config.include mechanism to include
it into your Pyramid project's configuration::

    config = Configurator(.....)
    config.include('pyramid_excel')

Alternately, you may activate the extension by changing your application's .ini file by
adding it to the pyramid.includes list::

    pyramid.includes = pyramid_excel

{%endblock%}
