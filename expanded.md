---
description: 可以自动填充的组件。
---

# Expanded

在Row组件中使用。

```dart
Row(
            children: <Widget>[
              //使用Expanded防止内容溢出
              new Expanded(
                child: new Container(
                  width: 150.0,
                  height: 150.0,
                  //添加边框样式
                  decoration: new BoxDecoration(
                    color: Colors.red,
                    //上下左右边框设置为宽度10.0 颜色为蓝灰色
                    border: new Border.all(width: 10.0, color: Colors.blueGrey),
                    //上下左右边框弧度设置为8.0
                    borderRadius:
                        const BorderRadius.all(const Radius.circular(8.0)),
                  ),
                  //上下左右增加边距
                  margin: const EdgeInsets.all(20.0),
                  //添加图片
                  child: new Image.asset('images/1.jpeg'),
                ),
              ),
            ],
          ),
```

