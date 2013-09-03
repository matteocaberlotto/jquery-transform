jquery-transform
================

A jquery plugin to help apply css transformation.

Simply pass object properties which will be merged to default.
Defaults are no rotation and no translation.

Examples:

Translate an object to (x = 100, y = 100):

``` js
$(".myClass").transform({
  dx: 100,
  dy: 100
});
```



Translate an object to (x = 100, y = 400, z = 200):

``` js
$(".myClass").transform({
  dx: 100,
  dy: 100,
  dz: 400
});
```


Translate an object and scale to 1/2:

``` js
$(".myClass").transform({
  dx: 100,
  dy: 100,
  dz: 400,
  scaleX: 0.5,
  scaleY: 0.5,
  scaleZ: 0.5
});
```


Rotate an object around z axis:

``` js
$(".myClass").transform({
  v3: 1,
  angle: 45
});
```

Rotate around y axis:

``` js
$(".myClass").transform({
  v2: 1,
  angle: 90
});
```

Reset position:

``` js
$(".myClass").transform();
```

