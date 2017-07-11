#  千锋笔记
## DAY1
### 1. 内联元素(行内元素)
`a`,`img(inline-block)`,`span`等
>内联元素排列在同一行，不能设置宽高，只能靠内容撑开
### 2. 块元素
`div`,`h`,`p`,`ul`,`ol`,`dl`,`li`等
>block元素独占一行，可以设置宽高
### 3. css权重
`id-100`, `class-10`, `tag-1`, `内联-1000`
### 4. 盒子模型
![盒子模型](/images/1.JPG)
### 5. CSS样式(http://www.w3school.com.cn/css3/index.asp)
## DAY2
### 1. 锚点（a）（http://www.w3school.com.cn/html/html_links.asp）
W3CSchool中讲的name属性在HTML5中已经被废弃，可以用id属性替代。
### 2. 块元素垂直居中
>方法一：父元素设置为相对定位，子元素绝对定位
```css
position: absolute;//绝对定位
top:0;
bottom: 0;
left: 0;
right: 0;
margin: auto;
```
>方法二：子元素相对定位,`top:50%;`,`margin-top:(设置为子元素高度的一般);`
```css
#outerBox{
    position: relative;
    width: 500px;
    height: 500px;
    border: 1px solid #212121;
    margin: auto;
}
#innerBox{
    width: 200px;
    height: 200px;
    border: 2px solid #409658;
    position: relative;
    margin: auto;
    top: 50%;
    margin-top: -100px;
}
```
![垂直居中](/imges/verticalMid.jpg)
### 3. 