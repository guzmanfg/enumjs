# EnumyJS

EnumyJS is a library to work with enum types easily in javascript.

## Installing

With NPM

```
npm install enumyjs
```

With Bower

```
bower install enumyjs
```

## How to use it

```
var enum = require('enum');
var MyEnum = enum.build(['RED', 'GREEN', 'BLUE']);
var myEnumInstance = new MyEnum(MyEnum.RED);
```

## Roadmap

### 0.1

* Inital code
    * Base (to be extended)
    * Enum
    * Flag
* Some testing