#记忆型

常规写法：

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

扩展写法：

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
```

```ad-info
**name="viewport"**：设备的屏幕上能用来显示我们的网页的那一块区域
```

| Name          | description                                                   |
|:------------- |:------------------------------------------------------------- |
| width         | 设置viewport的宽度，为一个正整数，或字符串"width-device"      |
| initial-scale | 设置页面的初始缩放值，为一个数字，可以带小数                  |
| maximum-scale | 允许用户的最大缩放值，为一个数字，可以带小数                  |
| minimum-scale | 允许用户的最小缩放值，为一个数字，可以带小数                  |
| user-scalable | 是否允许用户进行缩放，值为"no"或"yes"，no代表不允许yes代表允许 |
