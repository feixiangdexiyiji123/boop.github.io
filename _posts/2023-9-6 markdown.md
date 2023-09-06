# 第三天的markdown语法学习
## 基础语法
### 内嵌HTML标签
不懂，以后用到再说。  
## 扩展语法  
### 表格  
1.请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。  
2.可在表格任意一端添加。  
例如：  
\| Syntax      | Description |  
\| ----------- | ----------- |  
\| Header      | Title       |  
\| Paragraph   | Text        |  
表现为：  
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |  

3.连字符的数量变化可以改变代码的宽度，但呈现的输出相同。  
4.通过在标题行中的连字符的左侧，右侧或两侧添加冒号（:），实现对齐。 
例如：  
\| Syntax      | Description | Test Text     |  
\| :---        |    :----:   |          ---: |  
\| Header      | Title       | Here's this   |  
\| Paragraph   | Text        | And more      |  
表现为：  
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |  

5.可以添加链接，代码（仅反引号（`）中的单词或短语，而不是代码块）和强调。  
例如：  
\| a | b | c |  
\| :---: | :---: | :---: |  
\| d | e | f |  
\| g | h | i |  
表现为：  
| a | b | c |
|:-:|:-:|:-:|
| d | e | f |
| g | h | i |  

6.使用表格的HTML字符代码（&#124;）在表中显示竖线（|）字符,即使用代码替换竖线。  
例如：  
\| a |    b    | c |  
\|:-:|:-------:|:-:|  
\| d | e&#124;j | f |  
\| g |    h    | i |  
表现为：  
| a |    b    | c |
|:-:|:-------:|:-:|
| d | e&#124;j | f |
| g |    h    | i |  
