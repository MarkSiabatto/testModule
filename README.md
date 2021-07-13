# What is this?

Custom test module uploaded for GlobalSeis. Get the perfect shadow every time for the non-designer.

# Installation

`npm i moduleTestG6 --save`

Then...

```
import {moduleTestG6} from 'moduleTestG6';

moduleTestG6({
    shadow_type: 'soft',
    padding: false
});
```

## Options

moduleTestG6, while this is a test module to confirm load into NPM, the basic functionality includes 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)