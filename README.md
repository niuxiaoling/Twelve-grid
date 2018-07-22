# Twelve grid

Twelve grid的实现方式

> 前提是已经安装了sass
# commond 
```
  npm install -g node-sass
```
# 检查
```
 node-sass -v
```
# 建一个.scss 文件
> 右击打开命令行
```
node-sass css.scss aa.css --output-style expanded   //将scss文件编译为.css文件
```
### --output-style
- nested: 嵌套缩进的css代码。默认值
- expanded 没有缩进的，扩展的css代码
- compact 简洁格式的css代码
- compressed 压缩后的css代码
### 监控器-w,scss值改变后台就直接编译，不用再次更新
```
node-sass -w css.scss aa.css --output-style expanded
```
# 十二栅格
- 超大屏 1200 1170内宽 12 
- 大屏 992 970 12 
- 中屏 768 750 12 
- 小屏(手机屏) 100% 100% 12 
