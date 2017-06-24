## 1 避免不必要的媒体查询的方式

1 使用百分比取代固定长度，尝试使用与视口相关的单位\(vw vh vmin vmax\) 解析为视口宽度或高度的百分比

2 在较大分辨率下得到固定宽度时使用max-width代替width，它可以适应较小的分辨率且不需媒体查询

3 给替换元素\(img object video iframe等\)设置max-width=100%

4 需要背景图片完整铺满容器 background-size:cover

5 当图片或其他元素以行列式布局时，让视口的宽度来决定列的数量 flexbox和 display:inline-block加上常规的文本折行可以实现

6 使用多列文本时，指定列宽（cloumn-width）而不是指定列数\(cloumn-count\)

