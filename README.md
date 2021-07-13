# What is this?

Custom test module uploaded for GlobalSeis. Get the perfect shadow every time for the non-designer.

# Installation

`npm i testModuleG6 --save`

Then...

```
import {testModuleG6} from 'testModuleG6';

testModuleG6({
    shadow_type: 'soft',
    padding: false
});
```

## Options

testModuleG6, while this is a test module to confirm load into NPM, the basic functionality includes 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)