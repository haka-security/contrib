SMTP dissector
==============

Haka version: 0.2.0

Authors: Mehdi Talbi, Rémi Bauzac

License: MIT

Description
-----------

A simple SMTP dissector

Usage
-----

```lua
local smtp = require("smtp")

smtp.install_tcp_rule(25)
```

API
---

```lua
smtp.install_tcp_rule(port)
```

Events
------

  - command
  - response
  - mail_content
