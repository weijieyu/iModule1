# iModule1

移动端 无缝拖拽 轮播图 组件

基于zepto(default版)的

使用时，需要根据具体情况作出改动的地方

html
a链接的地址，图片路径

css
图片的width占满屏幕width使用的单位是10rem
即设置1 rem 定义为 document.documentElement.clientWidth/10
如果使用中rem定义不同，或者使用其他布局，注意修改img，img父级nav以及#slide的width

img的height，img父级#slide的height，#slide的height，提示圆点span的尺寸颜色

js
为了预防与引用处命名冲突，个人习惯用的变量名iNow，timer，size后均加上了数字7
