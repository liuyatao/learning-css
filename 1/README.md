# 一个相应式导航栏

## 效果
## 思路
1. 使用响应式媒体查询,当宽度小于`370px`的时候将菜单栏设置成`absolute`定位,并调整菜单栏样式。同时设置菜单打开/关闭按钮可见。
2. 通过给`nav-toggle`设置`active`属性设置nav-toggle的状态。
3.  通过给`nav-menu`设置`active`属性设置nav-menu的可见性。

## 一些关键点

1. 使用阿里iconfont设置伪类::before中的content来实现icon类按钮。
2. 相对定位中添加绝对定位的是应用。

