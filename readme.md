# GPS 坐标之间距离计算

> 引用

```
 npm install coordsdistance
```

> 使用方式

```
  const distance = require('coordsdistance');

  let coords = [[31.195864,121.580739],[31.195264,121.580439]];// [[lat,lng]];
  let lens = distance(coords);
  console.log(lens); //单位米
```
