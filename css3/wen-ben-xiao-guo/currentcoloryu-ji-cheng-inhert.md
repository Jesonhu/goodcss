## 1 currentColor

currentColor被解析为color 与当前元素某些颜色一致

css历史上第一个变量

```html
<!-- 水平分割线自动与文本颜色一致 -->
<div class="wrap1">
<hr class="hr" />
</div>
<div class="wrap2">
<hr class="hr" />
</div>
<div class="wrap3">
  ss
<hr class="hr" />
</div>
```

```css
.hr{
  height:3px;
  border:none;
  background-color:currentColor;
}
.wrap1 {
  color:red;
}
.wrap2 {
  color:blue;
}
.wrap3{
  border:1px solid green;
  border-color:green;
}
```

---

## 2 继承 inherit

可以用在任何css属性中，总数绑定父元素的计算值（伪元素取其继承元素）

#### 1 表单元素字体设定为与页面其他部分相同

```css
input, select, button {font:inhert}
```

#### 2 a链接颜色同页面中其他的文本颜色

```css
a {color:inhert}
```



