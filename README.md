lusty-log
=========

Version 1.0

add log publising to your context.

Require it in your config:

```lua
local config = {
  --...
  context = {
    ['context.log'] = { level = "debug" },
    ['context.store'] = {}
  }
  -...
}
```

call it:

```lua
context.log("debug", "a message")
```

License
-------
Copyright 2013 Olivine Labs, LLC. MIT licensed. See LICENSE file for details.
