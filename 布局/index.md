一端（两端）固定，其他自适应  
**flex布局**  
1，需要固定宽度或者长度的元素添加 

```
flex-shrink: 0;  
```
表示当元素放不下的时候，该元素不进行缩放  

2，自适应内容需要进行裁剪为...的时候使用下面样式

```
text-overflow: ellipsis;
white-space: nowrap;
overflow: hidden;
```
3, 可能要借助于 flex-wrap属性

```
.box{
  flex-wrap: nowrap | wrap | wrap-reverse;
}

//flex-flow是flex-direction 和 flex-wrap的简写
.box {
  flex-flow: <flex-direction> || <flex-wrap>;
}
```