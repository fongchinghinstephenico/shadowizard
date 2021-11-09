# What is this?

Get perfect shadows everytime for the non-designer.

# Installation

`npm i shadowizard --save`

// you often see people take their index.js (without the line module.exports.shadowizard = shadowizard;) and
// host it on a CDN, so that people who aren't using webpack or other bundlers can use the package.

Then... multiple code lines

```
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
})
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)