## 会动的简历
/* 
 * 面试官你好，我是XXX
 * 只用文字作做我介绍太单调了
 * 我就用代码来介绍吧
 * 首先准备一些样式
 */

*{
  transition: all 1s;
}
html{
  background: #eee;
}
#code{
  border: 1px solid #aaa;
  padding: 16px;
}

/* 我需要一点代码高亮 */

.token.selector{ color: #690; }
.token.property{ color: #905; }

/* 加一个呼吸效果 */

#code{
  animation: breath 0.5s infinite alternate-reverse;
}

#code{
  animation: breath 0.5s infinite alternate-reverse;
}

/* 现在正式开始 */

/* 我需要一张白纸 */

#code-wrapper{
  width: 50%; left: 0; position: fixed; 
  height: 100%;
}

#paper > .content {
 display: block;
}

/* 于是我就可以在白纸上写字了，请看右边 */

/* 接下来用一个优秀的库 marked.js
 * 把 Markdown 变成 HTML
 */




/*
 * 这就是我的会动的简历
 * 谢谢观看
 */