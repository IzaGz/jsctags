```js
function Ctor1() { this.x = 10; }
Ctor1.prototype = {a: 1};

function Ctor2() {}

var singleton = {a: 10, b: 20}; //: singleton

new Ctor1(); //: Ctor1
new Ctor2(); //: Ctor2
```
```json
[
  {
    "id": "108e6a40-7aef-11e6-a997-e73a4395a341",
    "name": "Ctor1",
    "addr": "/Ctor1/",
    "kind": "f",
    "type": "void function()",
    "lineno": 1,
    "origin": {
      "!span": "9[0:9]-14[0:14]",
      "!type": "fn()",
      "!data": {
        "isConstructor": true,
        "type": "Function.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108fc9d0-7aef-11e6-a997-e73a4395a341",
    "name": "prototype",
    "addr": "/prototype/",
    "kind": "v",
    "lineno": 2,
    "namespace": "Ctor1",
    "parent": "108e6a40-7aef-11e6-a997-e73a4395a341",
    "origin": {
      "!span": "40[1:6]-49[1:15]",
      "!data": {
        "isConstructor": false,
        "type": "Object.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108fc9d1-7aef-11e6-a997-e73a4395a341",
    "name": "a",
    "addr": "/a/",
    "kind": "v",
    "type": "number",
    "lineno": 2,
    "namespace": "Ctor1.prototype",
    "parent": "108fc9d0-7aef-11e6-a997-e73a4395a341",
    "origin": {
      "!span": "53[1:19]-54[1:20]",
      "!type": "number",
      "!data": {
        "isConstructor": false,
        "type": "Number.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108ff0e0-7aef-11e6-a997-e73a4395a341",
    "name": "Ctor2",
    "addr": "/Ctor2/",
    "kind": "f",
    "type": "void function()",
    "lineno": 4,
    "origin": {
      "!span": "70[3:9]-75[3:14]",
      "!type": "fn()",
      "!data": {
        "isConstructor": true,
        "type": "Function.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108ff0e1-7aef-11e6-a997-e73a4395a341",
    "name": "singleton",
    "addr": "/singleton/",
    "kind": "v",
    "lineno": 6,
    "origin": {
      "!span": "86[5:4]-95[5:13]",
      "!data": {
        "isConstructor": false,
        "type": "Object.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108ff0e2-7aef-11e6-a997-e73a4395a341",
    "name": "a",
    "addr": "/a/",
    "kind": "v",
    "type": "number",
    "lineno": 6,
    "namespace": "singleton",
    "parent": "108ff0e1-7aef-11e6-a997-e73a4395a341",
    "origin": {
      "!span": "99[5:17]-100[5:18]",
      "!type": "number",
      "!data": {
        "isConstructor": false,
        "type": "Number.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  },
  {
    "id": "108ff0e3-7aef-11e6-a997-e73a4395a341",
    "name": "b",
    "addr": "/b/",
    "kind": "v",
    "type": "number",
    "lineno": 6,
    "namespace": "singleton",
    "parent": "108ff0e1-7aef-11e6-a997-e73a4395a341",
    "origin": {
      "!span": "106[5:24]-107[5:25]",
      "!type": "number",
      "!data": {
        "isConstructor": false,
        "type": "Number.prototype"
      }
    },
    "tagfile": "__DIR__/objnames.js"
  }
]
```
```ctags
Ctor1	__DIR__/objnames.js	/Ctor1/;"	f	lineno:1	type:void function()
prototype	__DIR__/objnames.js	/prototype/;"	v	lineno:2	namespace:Ctor1
a	__DIR__/objnames.js	/a/;"	v	lineno:2	namespace:Ctor1.prototype	type:number
Ctor2	__DIR__/objnames.js	/Ctor2/;"	f	lineno:4	type:void function()
singleton	__DIR__/objnames.js	/singleton/;"	v	lineno:6
a	__DIR__/objnames.js	/a/;"	v	lineno:6	namespace:singleton	type:number
b	__DIR__/objnames.js	/b/;"	v	lineno:6	namespace:singleton	type:number
```
