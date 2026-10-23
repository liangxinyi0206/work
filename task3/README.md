# README
## 作业内容
完成一级导航菜单和二级下拉导航菜单两个网页。一级菜单采用表格布局横向导航；二级菜单使用ul列表实现横向主导航，鼠标悬浮可以展开二级下拉子菜单，两个html文件共用style.css样式表。

## 用到的标签
HTML：table、tr、td、ul、li、a、link
CSS：flex布局、position定位、:hover伪类、display控制元素显示隐藏

## 困难与解决
1. 二级下拉菜单不会隐藏：设置display:none隐藏，hover的时候改为display:block。
2. 下拉菜单位置偏移：父元素relative，子菜单absolute定位，放在父菜单下方。
3. ul自带圆点和边距：list-style:none清除圆点，重置margin、padding。