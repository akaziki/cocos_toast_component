# cocos_toast_component

一个简单的 tost 组件，用法：

```
 var Toast = reqire('Toast.js')
 Toast(text,{[gravity],[duration],[bg_color]})
```

- text:要显示的字符串
- gravity(可选):位置，String 类型，可选值('CENTER','TOP','BOTTOM'),默认为'CENTER'
- duration(可选):时间，Number 类型，单位为秒，默认 1s
- bg_color(可选):颜色，cc.color 类型，默认 cc.color(102, 102, 102, 200)
