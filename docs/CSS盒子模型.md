### 标准盒子模型



### IE盒子模型



### box-sizing属性
```css
div {
    box-sizing: border-box;
}

```
此时元素的内边距和边框不会增加它的宽度。可以所有元素都采用border-box模式
```css
* {
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
}
```
