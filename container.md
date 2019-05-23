# Container

```dart
decoration属性：添加边框样式。用BoxDecoration类
```

```dart
//添加边框样式
    decoration: new BoxDecoration(
        color: Colors.red,
            //上下左右边框设置为宽度10.0 颜色为蓝灰色
            border: new Border.all(width: 10.0, color: Colors.blueGrey),
            //上下左右边框弧度设置为8.0
            borderRadius:
                const BorderRadius.all(const Radius.circular(8.0)),
          ),
```

margin属性：上下左右增加边距

```dart
margin: const EdgeInsets.all(20.0),
```

