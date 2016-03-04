GuzzleBundle
============

[![Build Status](https://travis-ci.org/misd-service-development/guzzle-bundle.png?branch=master)](http://travis-ci.org/misd-service-development/guzzle-bundle)

This bundle integrates [Guzzle 3](http://guzzle3.readthedocs.org/) into your Symfony2 application, which takes the pain out of sending HTTP requests and the redundancy out of creating web service clients.

It can also integrate with the [JMSSerializerBundle](http://jmsyst.com/bundles/JMSSerializerBundle) for easy object (de)serialization, and provides a param converter for use with the [SensioFrameworkExtraBundle](http://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/).

Symfony 3 support
-----------------

Add to yout composer.json:

```
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/nullziu/guzzle-bundle"
        },
        {
            "type": "vcs",
            "url": "https://github.com/nullziu/guzzle3"
        }
    ],
```

Override guzzle dependency:
```
    "require": {
        "misd/guzzle-bundle": "dev-symfony3-compatible as v1.2.0",
        "guzzle/guzzle": "dev-symfony3-compatible as v3.10.0"
    },

```


Authors
-------

* Chris Wilkinson <chris.wilkinson@admin.cam.ac.uk>
* [The Symfony and Guzzle communities](https://github.com/misd-service-development/guzzle-bundle/contributors)

Documentation
-------------

Documentation is stored in the `Resources/doc/index.md` file in this bundle:

* [Read the documentation](Resources/doc/index.md)

Installation
------------

All the installation instructions are located in the [documentation](Resources/doc/index.md).

Reporting an issue or a feature request
---------------------------------------

Issues and feature requests are tracked in the [Github issue tracker](https://github.com/misd-service-development/guzzle-bundle/issues).
