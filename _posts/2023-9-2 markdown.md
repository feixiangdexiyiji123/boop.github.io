# 第二天的markdown语法学习  
## 基础语法  
### 分隔线  
1.创建分隔线，在空白行使用三个或多个星号、破折号、下划线，同时不能包含其他内容。  
2.为了兼容性，请在分隔线的前后添加空白行。  
例如：  
\***

\___  

\---  

表现为：  

***  

___  

---

### 链接
1.固定链接格式：【超链接显示名】（超链接地址 "超链接title"）。  
例如： 这是一个链接 \[Markdown语法](`https://markdown.com.cn`)。  
表现为： [Markdown语法](https://markdown.com.cn)  

2.给链接增加标题，即当鼠标悬停在链接上时显示的文字。  
例如：这是一个链接 \[Markdown语法](`https://markdown.com.cn` "最好的markdown教程")。  
表现为： [Markdown语法](https://markdown.com.cn "最好的markdown教程")
记得添加空格。  

3.使用尖括号。  
例如： <`https://markdown.com.cn`>  
<`1143010644@qq.com`>  
 表现为：<https://markdown.com.cn>  
 <1143010644@qq.com>  

 4.使文中链接失效，请在链接首尾添加反引号，就是键盘第二排第一个那个（~和`），当作code使用。  
 5.带格式的链接。  
 强调：在链接语法前后加星号，不是只在链接前后加星号。  
 斜体也是一样。  

 6.当链接中带有空格时，使用%20代替。  
 7.引用类型链接不懂，以后补充。  
 ### 图片  
 1.固定图片格式：`![图片alt](图片链接 "图片title")`。  
 例如：`![这是图片](https://csdnimg.cn/cdn/content-toolbar/csdn-logo_.png?v=20190924.1 "CSDN")`    
 ![这是图片](https://csdnimg.cn/cdn/content-toolbar/csdn-logo_.png?v=20190924.1 "CSDN")

 2.相关方法见：[Markdown插入图片，详细例子](https://blog.csdn.net/xapxxf/article/details/105133999)。  
 3.给图片添加链接：`[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)`  
 4.不知道为什么1的例子中的图片已经添加链接了。  
 ### 转义字符  
 1.利用反斜杠（\）来使加粗、斜体、分隔线、引用、列表等失效，表现出原来的字符。  
 
