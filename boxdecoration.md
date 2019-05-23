---
description: 在Container组件中使用，用来描述样式。（如线宽，线颜色等）
---

# BoxDecoration

```dart
Expanded(
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
```

