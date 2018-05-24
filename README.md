"css易忘的部分" 
1. 一行文本超出就隐藏并且显示省略号：

  overflow:hidden; //超出的文本隐藏

  text-overflow:ellipsis; //溢出用省略号显示

  white-space:nowrap; //溢出不换行
  
2.文本超出2行时隐藏并显示省略号：

  overflow:hidden; 

  text-overflow:ellipsis;

  display:-webkit-box; 

  -webkit-box-orient:vertical;

  -webkit-line-clamp:2; 
3.文本两端对齐
  text-align-last:justify
