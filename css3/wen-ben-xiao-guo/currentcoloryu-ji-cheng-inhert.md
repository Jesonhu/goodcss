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



