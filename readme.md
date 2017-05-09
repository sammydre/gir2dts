# gir2dts #

Generated *.d.ts files for using Gir with Typescript 

## install
```
cd myproject
npm install --save-dev gir2dts
```
then include in tsconfig.json

## example

Original example no longer valid. TDODO.

## rules
Conversion is iterative

* numeric typedefs are replaced with 'number'
* constructors are replaced with default having one optional hash table parameter
* constants, functions, enums, classes, structs (as classes). Properties included in classes
* anything else, not defined in this group of modules, gets replaced with 'any'
* as dicovered:
    * fix with add/patch entries in gir2dts.json



## differences

TBD

## why?

TODO. See original: https://github.com/darkoverlordofdata/gir2dts
