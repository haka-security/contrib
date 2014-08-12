Haka community contributions
============================

This repository gather all the Haka dissectors, modules and rules created by our community.

Organisation
------------

The community forge is organized as follows :

  - [protocols/](https://github.com/haka-security/contrib/protocols/) Contains all the protocol dissectors.
  - [modules/](https://github.com/haka-security/contrib/modules/) Contains all the Haka modules.
  - [rules/](https://github.com/haka-security/contrib/rules/) Contains all the Haka rules.


Contributing
------------

To share your own module you can either:

  - do a [pull request](https://github.com/haka-security/contrib/compare/)
  - send an email to haka-security@arkoon.net

Your contribution must contain at least :

  - ``examples/`` A directory containing at least one example of a rule using the module.
  - ``README.md`` A short reference file for your module with the following
    template.

```Markdown
<Contribution name>
===================

Haka version: <version>

Author: <author>

License: <license>

Description
-----------

A short description.

Usage
-----

An example of how to load and use your module.

API
---

A list of the functions exposed by your module
```

If your module is a dissector it must also have:

```Markdown
Events
------

A list of the events exposed by your module

 - myevents
 - ...
```
