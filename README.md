# TypeScript Essentials
Learning TypeScript. Review of ES6 features

## Compile TypeScript
- manual: tsc <nameoffile>  or
          tsc -w <nameoffile>  (to keep watch and continually compile as save changes)
- better automatic:
  - create tsc config file name tsconfig.json
  include "complierOptions", etc.
  - then from command line: tsc -w
    to watch all files

## ES6
- Optional parameters: add = value after param name to add
- Template strings: use back ticks (` `)  and ${ } to add in JS expressions.
