# 浙大竺可桢学院[实用技能拾遗]
# LaTeX排版简要介绍
``` bash
>>> texdoc package   # 查看宏包文档,package 填文档明 
```

### 段落
- 空行或\par分段
- 行首空格会被省略，多个空格会被合并
- 换行在非中文语境下视作一个空格

### 断行与断页
- 可以用 \\\ 或 \newline 强制换行
  - 类似word中的软回车，不会产生新的段落
- \newpage 强制断页
- \clearpage 强制断页并清空浮动体
  - 一般用 \newpage 就好

### 字形与字号
- 有两类修改字形的命令
  {\bfseries bold} 和 \textbf{bold}
  - 前者对此处之后的都生效  后者只对参数内容生效
  - 都是内置字体的不同样式
- 修改字号：{\large Hi}
- **汉字一般不使用斜体**
- **不要滥用字体样式**
- ![alt text](../pic/latex_image_0.png)

### 字符与标点
- 西文语境下的引号要这么打：``double''
  - 中文语境下正常输入即可
- 连字符：-、 短破折号：--、 长破折号：---
- 防止西文连字 dif{}f{}icult

### 强制行距/间距
![alt text](../pic/latex_image_1.png)

### 标题页
在导言区
- \title{title}：标题
- \author{author}：作者
- \date{date}：日期，不写则默认为当前日期\today
在正文区使用\maketitle生成标题页

### 环境
![alt text](../pic/latex_image_2.png)

### 章节和目录
![alt text](../pic/latex_image_3.png)

### 图片
![alt text](../pic/latex_image_4.png)
### 浮动体
![alt text](../pic/latex_image_5.png)![alt text](../pic/latex_image_6.png)

### 数学模式
![alt text](../pic/latex_image_7.png)
![alt text](../pic/latex_image_8.png)
> align环境下&可以用来对齐
> \begin{align*}可以取消每行编号

![alt text](../pic/latex_image_9.png)
![alt text](../pic/latex_image_10.png)
\vdots  vertical垂直的
\ddots  diagonal

### 括号与定界符
![alt text](../pic/latex_image_11.png)

### 特殊数学字体
![alt text](../pic/latex_image_12.png)
### 规范写法
![alt text](../pic/latex_image_13.png)
![alt text](../pic/latex_image_14.png)

### 列表
![alt text](../pic/latex_image_15.png)

### 对齐环境
![alt text](../pic/latex_image_16.png)

### 代码环境
![alt text](../pic/latex_image_17.png)



